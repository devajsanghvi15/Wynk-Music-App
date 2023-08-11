# Wynk-Music-App
## DSA course project (3rd semester)
### Problem Statement
The task is to build a console based music streaming application which has functions like create a playlist, play specific songs, count the number of songs in the playlist that are implemented using Data structures and Algorithms. Wynk is a musical application in which the above-mentioned functions are included.

The drawback of Wynk is that we cannot sort songs in the playlist according to the released year. We had overcome this drawback by implementing an algorithm known as Bubble sort. Similar to this function many other functions are present in this application which can be built using various algorithms.
### Functionalities
|S.No.|Function Name|Description|Data structure and algorithm used|Efficiency|
|:-----:|:-------------:|:-----------:|:--------------------------------:|:----------:|
|1.|login|Allows user to login using his/her credentials|-|-|
|2.|registration|Allows user to sign up|-|-|
|3.|insert_song|Adds a song to the playlist|Circular doubly linked list|O(N)|
|4.|delete_song|Deletes a song from the playlist|Circular doubly linked list|O(N)|
|5.|display_playlist|Prints all the songs present in the playlist|Circular doubly linked list|O(N)|
|6.|play_first_song|Plays the first song in the playlist|Circular doubly linked list|O(1)|
|7.|play_last_song|Plays the first song in the playlist|Circular doubly linked list|O(1)|
|8.|display_by_language|Prints all the songs of a particular language|Circular doubly linked list|O(N)|
|9.|play_prev|Play the previous song|Circular doubly linked list|O(1)|
|10.|play_next|Play the next song|Circular doubly linked list|O(1)|
|11.|count|Prints the number of songs present in the playlist|Circular doubly linked list|O(N)|
|12.|search_and_play|Used to play a song by searching|Naive’s Algorithm|O(N<sup>2</sup>)|
|13.|sort|Sorts all the songs in a playlist by the year released|Bubble Sort Algorithm|O(N<sup>2</sup>)|
|14.|display_recently_searched|Displays all the recently searched songs|Array of structures|O(N)|
|15.|display_curr_song|Displays currently playing song|Circular doubly linked list|O(1)|
### Data Sructures and Algorithms
|S.No.|Data Structure and Algorithm used|Description|Efficiency|Order of Growth|
|:---:|:-------------------------------:|:---------:|:---------:|:-------------:|
|1.|Naive’s Algorithm|Naive’s algorithm is simple and easy to implement. It handles both continuous and discrete data.|O(N<sup>2</sup>)|O(N!)|
|2.|Circular doubly linked list|Insertion and deletion operations are efficient and easily implemented as compared to other data structures like array.|O(N)|O(N)|
|3.|Bubble sort|Bubble Sort is the simplest sorting algorithm that works by repeatedly swapping the adjacent elements if they are in the wrong order.|O(N<sup>2</sup>)|O(N<sup>2</sup>)|
|4.|Brute Force Algorithm|This is the most basic and simplest type of algorithm. In the end it definitely gives the optimal solution.|-|O(N)|
|5.|Array of Structures|It is used to store the names of recently searched songs and display them when required.|O(N)|O(N)|

Note: To run the code download "code and essentials.zip" and unzip it in one folder. Then run main.c
