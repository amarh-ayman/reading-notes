# Hash Tables

## Definitions

## What is a hashtable

> Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
> Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
> Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Uses

- Hold unique values
- Dictionary
- Library

### Hashtables are a data structure that utilize key value pairs

### Hashtable works according to the priciple of storng the key into the data structure/hashtables, and quickly retrieve the value.

### This is done through hash, which is a way to encode the key

### Example

> ["Greenwood:98103", "Downtown:98101", "Alki Beach:98116", "Bainbridge Island:98110"]

# Structure

## Hashing

- hash transforms key into a an integer
- hash codes are deterministic, such the output depends on the input only

## How a Hash is Created?

- **Steps**
- > - Add or multiply all the ASCII values together.

  - Multiply it by a prime number such as 599.
  - Use modulo to get the remainder of the result, when divided by the total size of the array.
  - Insert into the array at that index.

- **Example**
  > Key = "Cat"
  > Value = "Josie"

67 + 97 + 116 = 280

280 \* 599 = 69648

69648 % 1024 = 16

Key gets placed in index of 16.

## Hashmap Example:

> SUM HASHED: Pioneer Square = 1379
> SUM HASHED: Alki Beach = 884
> SUM HASHED: U District = 955

BUCKET SIZE=99
SUM INDEX: 1379 % 99 = 92
SUM INDEX: 884 % 99 = 92
SUM INDEX: 995 % 99 = 64

## Internal Methods

- Add()

- Find()

  > The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index location is found in the array, it is then the responsibility of the algorithm the iterate through the bucket and see if the key exists and return the value.

- Contains()

  > The Contains method will accept a key, and return a bool on if that key exists inside the hashtable. The best way to do this is to have the contains call the GetHash and check the hashtable if the key exists in the table given the index returned.

- GetHash()
  > The GetHash will accept a key as a string, conduct the hash, and then return the index of the array where the key/value should be placed.
