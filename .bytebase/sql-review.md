# .bytebase/sql-review.md
# SQL Review Standards

## 1. Table Naming Convention
- All table names must be in snake_case
- Avoid abbreviations unless commonly understood

## 2. Column Standards
- Primary key columns should be named 'id'

## 3. Index Requirements
- Columns used in WHERE clauses frequently should be indexed

## 4. Comment Requirements
- Complex columns should have comments explaining their purpose

## 5. Type Consistency
- Use TEXT instead of VARCHAR for string columns
- Use TIMESTAMP for datetime values
- Use BIGINT for auto-incrementing primary keys
