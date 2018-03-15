



## Random Arbiters Selection

There are couple methods to get randomness in deterministic environment such as blockchain . For arbiter selection we use Commit-Reveal scheme, basic workflow : 



1\) Customer opens an DRM 

2\) Customer software call a DRM extension smart contract 

3\) DRM extension call a Pool smart contract, where it selects appropriate arbiters pool

4\) _**Pool Master**_ starts a _**Commit Phase**_ by submitting hashed salt 

5\) Customer 1 submit hashed salt

6\) Customer 2 submit hashed salt

![](/assets/commit.png) 



7\)If all parties sumbited their hashes, _**Reveal Phase  **_can be started_**.**_ 

8\) Customer 1 reveals his hash 

9\) Customer 2 reveal his hash

![](/assets/random.png)

10\) Based on customers and his salt, _**Pool master **_generates a random number and secelects Arbiters based on this number 





