# Postgres index types
https://www.postgresql.org/docs/9.2/static/indexes-types.html

## B-Tree index is what you most commonly want
CREATE INDEX use this index type

## GIN indexes (Generalized Inverted Indexes), which can handle values that contain more than one key
hStore, Arrays, Range types, JSONB
https://www.postgresql.org/docs/10/static/textsearch-indexes.html

## GiST indexes, for rows that overlap values
Geometry types, Text when dealing with full-text search

## SP-GiST indexes, for larger data

## BRIN indexes, for larger data

## Hash indexes
