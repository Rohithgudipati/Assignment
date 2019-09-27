# Assignment

# <h3>1. Micro and Array Update</h3>
Micro purchased an array A having N integer values. After playing it for a while, he got
bored of it and decided to update value of its element. In one second he can increase
value of each array element by 1. He wants each array element's value to become greater
than or equal to K. Please help Micro to find out the minimum amount of time it will take,
for him to do so.
# <h4>Input:</h4>
First line consists of a single integer, T, denoting the number of test cases.
First line of each test case consists of two space separated integers denoting N and K.
Second line of each test case consists of N space separated integers denoting the array
A.
# <h4>Output:</h4>
For each test case, print the minimum time in which all array elements will become
greater than or equal to K. Print a new line after each test case.
Constraints:
1<=T<=5
1<=N<=10^10
1<=A[i],K<=10^6

# <h4>SAMPLE INPUT</h4>
2<br>
3 4<br>
1 2 5<br>
3 2<br>
2 5 5<br>
# <h4>SAMPLE OUTPUT</h4>
3<br>
0

# <h3>2. Hamiltonian and Lagrangian</h3>
Students have become secret admirers of SEGP. They find the course exciting and the
professors amusing. After a superb Mid Semester examination, it’s now time for the
results. The TAs have released the marks of students in the form of an array, where arr[i]
represents the marks of the ith student.
Since you are a curious kid, you want to find all the marks that are not smaller than those
on its right side in the array.
# <h4>Input Format</h4>
The first line of input will contain a single integer n denoting the number of students.
The next line will contain n space separated integers representing the marks of students.
# <h4>Output Format</h4>
Output all the integers separated in the array from left to right that are not smaller than
those on its right side.

# <h4>Constraints</h4>
1 <= n <= 1000000
0 <= arr[i] <= 10000

# <h4>SAMPLE INPUT<h4>
6<br>
16 17 4 3 5 2
  # <h4>SAMPLE OUTPUT</h4>
17 5 2<br>

# <h3>3. Frustrated coders</h3>
There are N frustrated coders standing in a circle with a gun in their hands. Each coder
has a skill value S[ i ] and he can only kill those coders that have strictly less skill than
him. One more thing, all the guns have only 1 bullet. This roulette can take place in
any random order. Fortunately, you have the time stone (haaan wo harre wala) and
you can see all possible outcomes of this scenario. Find the outcome where the total
sum of the remaining coder's skill is minimum. Print this sum.
# <h4>Input Format</h4>
The first line contains N the no. of coders
The next line contains N elements where the ith element is theS[ i ] of ith coder.
# <h4>Output Format</h4>
Print a single line containing the minimum sum.

# <h4>Constraints</h4>
1<= N <= 1000000
1<=S[ i ]<=1000
# <h3>4. Pink Floyd and Happiness</h3>
Pink is sad because of some reasons, he wants to cheer up by listening to some songs
from his favorite band, Pink Floyd.
There are N records and Pink will be happy if he listens to them in the ascending
order, i.e., first the song No. 1, then No.2 and so on (He has to listen to all the N songs
to become Happy).
Pink is delivered his records in some given order, he can either add the record to the
Playlist in the delivered order or put some on another table. After being put on the
table only the topmost record can be added to the playlist at any time.
Print whether Pink will be sad or happy after the delivery of the records.
# <h4>Input Format</h4>
N - Number of records followed by
N numbers- order of records.
# <h4>Output Format</h4>
Print "Happy" if the playlist has songs from 1 to N in order else "Sad".

# <h4>Constraints</h4>
1<=N<=10^5
The array consists of 1-N distinct numbers.

# <h3>6. Remove Friends</h3>
After getting her PhD, Christie has become a celebrity at her university, and her
Facebook profile is full of friend requests. Being the nice girl, she is, Christie has
accepted all the requests.
Now Kuldeep is jealous of all the attention she is getting from other guys, so he asks
her to delete some of the guys from her friend list.
To avoid a 'scene', Christie decides to remove some friends from her friend list, since
she knows the popularity of each of the friend she has, she uses the following
algorithm to delete a friend.
# <h4>Algorithm Delete(Friend):</h4>
DeleteFriend=false
for i = 1 to Friend.length-1
if (Friend[i].popularity < Friend[i+1].popularity)
delete i th friend
DeleteFriend=true
break
if(DeleteFriend == false)
delete the last friend.
# <h4>Input Format</h4>
First line contains T number of test cases. First line of each test case contains N, the
number of friends Christie currently has and K ,the number of friends Christie decides
to delete. Next lines contains popularity of her friends separated by space.
# <h4>Output Format</h4>
For each test case print N-K numbers which represent popularity of Christie friend's
after deleting K friends.
<h4>Constraints</h4>
1<=T<=1000
1<=N<=100000
0<=K< N
0<=popularity_of_friend<=100

8

# <h4>NOTE:</h4>
Order of friends after deleting exactly K friends should be maintained as given in
input.

# <h3>SAMPLE INPUT</h3>
3<br>
3 1<br>
3 100 1<br>
5 2<br>
19 12 3 4 17<br>
5 3<br>
23 45 11 77 18<br>

# <h3>SAMPLE OUTPUT</h3>
100 1 <br>
19 12 17 <br>
77 18 
