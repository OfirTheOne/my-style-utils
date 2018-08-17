# Style Utils
My style utils scss css classes and stuff.


## Spacing 

* `$balancer` value is 4px

### Margins Classes :

:one:  -  Margin Surrounder Class
```  
class structure :
-----------------
 .m-n1-n2-n3-n4
  
  
about :
-------
 n1-n2-n3-n4 stands for the margin sides - top-right-bottom-left. 
 n1, n2, n3, n4 values can be from 0 to 4, each will be multiply be the balancer value.
    
    
exemple :
---------
 .m-2-4-2-1 {                                                            
      margin: 2*$balancer 4*$balancer 2*$balancer 1*$balancer;     
 } 
       =
          
 .m-2-4-2-1 {   
      margin: 8px 16px 8px 4px;
 }
```



