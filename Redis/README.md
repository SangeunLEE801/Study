# Redis

Redis(*R*emote *DI*ctionary *S*erver) is an open source, in memory data structure store, used as a database, cache and message broker.

#### 1. Key Value store.
ex) command -> redis key-value store

`SET "name" "John"` -> name: John

`SET "age" "25"` -> age : 25

`GET "name"` -> John

#### 2. No sql -> easy to use
- Does not have tables, columns/rows etc like traditional sql databases(oracle)
- Does not uses SELECT, INSERT, DELETE, UPDATE

#### 3. Uses data structures to store data
- strings, hashes, lists, sets, sorted sets (primary data structures)
- bitmaps, hyperloglogs and geospatial indexes (extra data structures)

#### 4. In-memory db
- make it very fast -> one of the highlighted features of redis
- has an option to write data on disk

#### 5. cross platform system (support multi language)

#### 6. master-slave replication feature
- master : write only
	- slave1: read only
	- slave2: writes data to disk

#### 7. single thread: one action at a time

