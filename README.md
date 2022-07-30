// reverse
var num=prompt()
var len=num.length
var n=num
var i=len-1
var sum=0
while(n>0)
  {
    rem=n%10
    sum=sum+rem*Math.pow(10,i)
    n=Math.floor(n/10)
    i=i-1
  }
document.write("original number : "+num+"<br><br>"+"reverse number : " + sum)

