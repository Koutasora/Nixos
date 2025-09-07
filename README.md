/etc/nixos/configuration.nix → Folder docelowy świeżego systemu

po instalacji wrzucamy do pliku git i uruchamiamy klonowanie

```git clone (link) .dotfiles```  

```ssh-keygen```  
```cd .ssh```
```ls```
```cat```  


```git remote origin```  
```git remote rm origin```  
```git remote add github (link)```  
```git remote github```  

Rebuild  
```sudo nixos-rebuild switch```  <- standardowo przebudowuje system  
```sudo nixos-rebuild switch --flake .``` <- Ustawia flake z .dotfiles 
