LAB3
====

#Prelab

Schematic for Nexys2_top_shell.vhd

![alt tag](http://s23.postimg.org/v34a5b3ej/2014_03_16_21_17_56.jpg)


#Main LAB


###BAD
```
nibble0 <= 
nibble1 <= 
nibble2 <= 
nibble3 <=

```
We don't have any values assigned. 

###GOOD

#######MORE
```
nibble0 <= floorSig(3 downto 0);
nibble1 <= "0000";
nibble2 <= "0000";
nibble3 <= "0000";
```
#######Mealy
```
nibble0 <= floorSig(3 downto 0);
nibble1 <= nextFloorSig;
nibble2 <= "0000";
nibble3 <= "0000";
```
We have values assigned. "nibble1" is different in both machines because in Mealy machine we want "second" digit to show us our target floor.

Error wise everything else looks good.

##Demos:
Capt Silva check my machine at 11:15 on 17 March.


####Documentation:

C3C Spence helped me to understand the concept. 
Capt Silva helped me with github problems which occured because of to me repositories.


