Java端
```
public static void main(String args[]) { 
  try{  
   //Javaプログラム入口  
  }catch(Throwable t){  
    t.printStackTrace();  
    System.exit(異常コード)  
  }  
}

//業務処理
public void m(){
  throw new RuntimeException("This is a business error!!")
}
```

shell端  
```
Java -jar program.jar  
echo $?  
```
$?はJavaの異常コード  
