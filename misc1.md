
Tool I used to solve this challenge is google search engine. This challenge was introduced with a text file called tryme.txt which contains some 280 lines of code. With my terrible coding skill, I started with the last line of the code which was starting with something like this: 

        `ﾟωﾟﾉ= /｀ｍ´）ﾉ ~┻━┻   //*´∇｀*/ ['_']; o=(ﾟｰﾟ)  =_=3; c=(ﾟΘﾟ) =(ﾟｰﾟ)-(ﾟｰﾟ); (ﾟДﾟ) =(ﾟΘﾟ)= (o^_^o)/ (o^_^o);(ﾟДﾟ)={ﾟΘﾟ: '_' ,ﾟωﾟﾉ : ((ﾟωﾟﾉ==3) +'_') [ﾟΘﾟ] ,ﾟｰﾟﾉ :(ﾟωﾟﾉ+ '_')[o^_^o -(ﾟΘﾟ)] ,ﾟДﾟﾉ:((ﾟｰﾟ==3) +'_')[ﾟｰﾟ] }; (ﾟ  
    

I searched this line of code in google and got to know about something called aaencoding. This is some kind of obfuscator for JS. I searched for online decoders and got the following link:
https://cat-in-136.github.io/2010/12/aadecode-decode-encoded-as-aaencode.html 
When I decoded the last line of the code, I got the following decoded value:
alert("Hello flag{flags_are_useless_in_real_world}")
So the flag for misc1 was: flag{flags_are_useless_in_real_world}
