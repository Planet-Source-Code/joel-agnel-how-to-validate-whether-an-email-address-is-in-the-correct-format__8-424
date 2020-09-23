<div align="center">

## How to validate whether an email address is in the correct format


</div>

### Description

This code will explain how to validate an email address and then accept it for processing/using. If you find this code useful, please vote for me.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Joel Agnel](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/joel-agnel.md)
**Level**          |Beginner
**User Rating**    |4.3 (13 globes from 3 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Validation/ Processing](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/validation-processing__8-16.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/joel-agnel-how-to-validate-whether-an-email-address-is-in-the-correct-format__8-424/archive/master.zip)





### Source Code

```
<PRE>
<font size=2 face=verdana,arial,helvetica>
&lt;?
// Author : Joel Agnel
$address = "name@emailaddress.com";
//The email address that is to validated
$expression = "^[_A-Za-z0-9-]+@[_A-Za-z-]+(\.[A-Za-z]+)(\.[A-Za-z]+)*$";
//The expression that describes
//the pattern the address should have
if(!ereg("$expression",$address)) { &nbsp;&nbsp;//if $address is not matching to $expression
echo "Sorry wrong address"; &nbsp;&nbsp;// not valid
} else {  &nbsp;&nbsp;&nbsp;// else it is valid
echo "The address is valid";
}
?&gt;
<a href="mailto:joelagnel@siteskool.com">Email me</a> for any help with this code
</PRE>
```

