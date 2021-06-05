# Pain vs. Suffering

It is important to prepare ourselves mentally for the pain we’re expected to experience in the coming 10-week spectacular learning journey. A good thing to keep in mind is that the pain won’t be aimless, it won’t be suffering. It’ll be pain in favor of growth.
<br><br>

# Big O notation

Big O notation is:
used in Computer Science to describe the performance or complexity of an algorithm.

describes the worst-case scenario, and can be used to describe the execution time required or the space used (e.g. in memory or on disk) by an algorithm.

Common Orders of Growth:

- O(1)

describes an algorithm that will always execute in the same time (or space) regardless of the size of the input data set.

**Example:**<br>

> bool IsFirstElementNull(IList elements) {return elements[0] == null;}

- O(N)

An algorithm with linear behaviour and is directly proprtional with the input data set size.

**Example(showing how this order favours the worst-case performance scenario):**

> bool ContainsValue(IEnumerable string> elements, string value) { foreach (var element in elements) { if (element == value) return true; }
> return false; }

- O(N²)

An algorithm that is directly proprtional with the square of the input data set size.
common among algorithms with nested iterations over the data set.
**Example:**

> bool ContainsDuplicates(IList elements) { for (var outer = 0; outer < elements.Count; outer++) { for (var inner = 0; inner < elements.Count; inner++) { // Don't compare with self if (outer == inner) continue;

> if (elements[outer] == elements[inner]) return true;
> }
> }
> return false; }

<br><br>
![img](https://www.codingninjas.com/blog/wp-content/uploads/2021/01/image-21.png)
<br><br>

- O(2^N)

an algorithm whose growth doubles with each addition to the input data set.

The growth curve of an O(2^N) function is exponential — starting off very shallow, then rising meteorically.

Example:
recursive calculation of Fibonacci numbers

## Another O Natation

<br>

- O(log n), also known as log time. Example: Binary search.

- O(n), also known as linear time. Example: Simple search. (for more details 👆👆)

- O(n \* log n). Example: A fast sorting algorithm, like quicksort.

- O(n2). Example: A slow sorting algorithm, like selection sort.

- O(n!). Example: A really slow algorithm, like travelling salesperson.
  <br><br>
  ![complexity](https://www.freecodecamp.org/news/content/images/2020/03/31781165-723a053c-b500-11e7-937c-7b33db281efe.png)
