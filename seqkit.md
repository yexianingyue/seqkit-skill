# seqkit

如果要处理序列，应该首先想到此软件
下载地址：[下载](https://bioinf.shenwei.me/seqkit/download/)

##1、amplicon    

##2、bam         

##3、common      

##4、concat      

##5、convert     

##6、duplicate   

##7、faidx       

##8、fish        

##9、fq2fa       

##10、fx2tab     

##11、genautocomp

##12、grep       

##13、head       

##14、help       

##15、locate     

##16、mutate     

##17、range      

##18、rename 

__只是重命名id重复,不是单纯的改名字__

改序列名称推荐：seqtk rename

```sh {cmd=true}
./software/seqkit rename -h
```
### 18.1、example

```sh {cmd=true}
echo -e ">a comment\nacgt\n>b comment of b\nACTG\n>a comment\naaaa"
```
```sh {cmd=true}
echo -e ">a comment\nacgt\n>b comment of b\nACTG\n>a comment\naaaa"  | ./software/seqkit rename

```


##19、replace    

参数一览
```sh {cmd=true}
echo -e ">abd\nATCGXXX"| ./software/seqkit.exe replace -p "X" -r "N" -s 
```

```sh {cmd=true}
echo -e ">seq1\nACTGACGT\n>seq2\nactgccgt"  | ./software/seqkit replace -p "(.)" -r     "\$1 " -s
```

```sh {cmd="./software"}
seqkit -h
```

```shell {cmd="powershell.exe"}
tree
```

##20、restart    

##21、rmdup      

##22、sample     

##23、sana       

##24、seq        

##25、shuffle    

##26、sliding    

##27、sort       

##28、split      

##29、split2     

##30、stats      

##31、subseq     

##32、tab2fx     

##33、translate  

##34、version    

##35、watch      
