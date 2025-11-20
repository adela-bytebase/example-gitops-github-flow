# .bytebase/sql-review.md
# SQL Review Standards

## 1. Table Naming Convention
- All table names must be in snake_case
- Table names should be plural nouns (e.g., users, orders, products)
- Avoid abbreviations unless commonly understood

## 2. Column Standards
- Every table must have a created_at timestamp column
- Every table must have an updated_at timestamp column
- Primary key columns should be named 'id'

## 3. Index Requirements
- Foreign key columns must have indexes
- Columns used in WHERE clauses frequently should be indexed

## 4. Comment Requirements
- All tables must have descriptive comments
- Complex columns should have comments explaining their purpose

## 5. Type Consistency
- Use TEXT instead of VARCHAR for string columns
- Use TIMESTAMP for datetime values
- Use BIGINT for auto-incrementing primary keys
