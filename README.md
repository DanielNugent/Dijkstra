# Edsger Wybe Dijkstra

# Life

Dijkstra was born in Rotterdam in The Netherlands. His father was a chemist and his
mother was a mathematician. He initially desired to study law, but instead with his
parent’s advice, studied mathematics and physics at Leiden University in his home
country in 1948. It would be 1952 where his career would completely shift direction, as
one of his supervisors would offer him a job in computing and officially became The
Netherland’s first “programmer”. After programming for some years, he married Maria
C. Debet’s in 1957 and then soon after in 1959 got his PhD for his thesis on
“Communication with an Automatic Computer”.

Between 1952 and 1962 Dijkstra worked in his first job which was to build a computer.
Here he learned the fundamentals of software engineering which was in its infancy at
the time. He learned how to write documentation for the software which he was
writing, which his colleagues would build the hardware aspect of the machine. In 1956
he solved the shortest path problem and the algorithm he developed is now very
famous and is named after him.

For the next decade or so he worked as a professor in Eindhoven and Neunen in the
mathematics department as Computer Science wasn’t an established field at the time in
The Netherlands. In 1973 he started working for the Burroughs Corporation, which was
making computers at the time. He worked in his home in Nuenen and visited the
company’s branches in the United States. He was still employed as a professor a
University at the time but significantly reduced his working hours there to
accommodate for his new position. He worked in the University on Tuesday and became
known as the “Tuesday After Club”, which became essentially seminar where he would
convene professors and other professions and discuss literature regarding computer
science and solve problems. In 1984 he moved to the University of Texas at Austin and
another form of this Tuesday After Club was formed there.

He would work there until 1999, until he retired. He unfortunately got diagnosed with
cancer and passed away on the 6th of August 2002 at just 72 years of age.


# Major Contributions to Computer Science

## Some Algorithms

Dijkstra is most famous for his Algorithmic work. We briefly touched on his famous
Dijkstra algorithm which is now studied by nearly every college student who takes
Computer Science and Mathematics worldwide. The algorithm is used to find the
shortest path in a weighted graph between any two nodes. It is now used in OSPF and
IS-IS where are routing protocols used to route the sending and receiving of packets
across routers. I used the algorithm last year in telecommunications to traverse routers
and find the fastest way to send a packet of information between sender and receiver.
The algorithm is not complex, but still is quite efficient at it’s purpose. Most of the new
algorithms built to accomplish this task have been based on the original algorithm
proposed by Dijkstra in 1956. Improvements include reducing runtime and the search
space.

Although not the original inventor of this next algorithm, he recreated Prim’s algorithm
when attempting to solve a problem which involved reducing wire usage to connect pins
on a computer.

In 1961 he rediscovered the shunting yard algorithm which parses expressions defined
in infix notation (such as 2*3-3+1) and returns the same expression in Reverse Polish
notation. (that same equation would be 2 3 * 3 – 1 +). I implemented this algorithm in
2 nd year in the Systems Programming module in C. It is quite incredible that 60 years
later his work is still being used widespread in Computer Science.

In 1963 he discovered the semaphore mechanism used in concurrency for mutual
exclusion. It is extremely similar to Dekker’s algorithm which I studied during the
Concurrent Systems and Operating Systems module last year. The purpose is that if two
processes want to access a critical section simultaneously, the algorithm will prevent
them doing so and only allow one process in at a time to prevent errors, which
guarantees mutual exclusion and prevents any deadlocks from occurring.

He was interested in garbage-collection, the process of the automatic deallocation of
memory that is no longer be used and allowing it to be reused. He formalized tri color
marking, which is a method of garbage collection that is widespread nowadays.

He developed the smoothsort algorithm in 1981, which is a variation of the heapsort
algorithm and runs in 푂(푛 푙표푔 푛)_._ It is not stable however but can run close to 푂(푛) if
the input has some parts already sorted.


## Software Engineering

Dijkstra said that programming was a discipline, not a craft. Dijkstra’s views of
programming gave rise to structured programming, which was a new concept at the
time. The main ideas of it were that software development should be structured and
rational. Software Crisis is a term for the early days of software engineering where there
were no standards in place to safeguard the development of software. Issues typically
included projects running over time and budget, and low-quality slow code. Dijkstra said
that “The major cause of the software crisis is that the machines have become several
orders of magnate more powerful!”. If there were no computers, software engineering
was non existential, so you didn’t have any problems. He advocated against the use of
the “GOTO” statement, which is not seen in modern programming languages, but can
be seen in C, C++ and more low-level languages. His argument against it was simply that
it contributed to many errors and interrupted control flow in an unnatural way. This is
one of the main concepts of structured programming, as it is often referred to as “a
goto-less programming”.

# Conclusion

Dijkstra was an extremely influential figure of everything computer science. From
algorithms, to compilers and operating systems to even software engineering, he
contributed and furthered its development. He gets the recognition he deserves for his
work in the field. In 1972 he was awarded the Turing award for his work. The award
signifies incredible achievement in the field of computer science. Dijkstra is a figure
many people in computing look up to for inspiration and has solidified his position in the
computing hall of fame.



