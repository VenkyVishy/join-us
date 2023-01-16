# `twob || !twob`

Please put your responses in a file
called `answers.md`. And yes! our humor is dry 🏜

## Introductions

- Who are you? What do you like building? I am Vengatesh R from Pondicherry, India. I am an Associate Tech specialist as well as UDC (Accounts department). I like compiling and building new programs and creating responses to the challenges issued on the 
- Do you own a PC and have a good internet
 connection? Let's hear those specs 💪! I have a good internet connection, because I have optical fibre internet connection at home at the maximum rate of 100 Mbps per second. I have my own laptop by the brand manufacturer called Asus, it runs on a processor called Intel i5 10th generation and it runs on a graphics card called AMD Radeon.
- Your stackoverflow, linkedin, personal site.
Anything you'd want us to see.https://www.linkedin.com/in/vengatesh-vishy-36212640/
vengateshrsempire.art.blog
- What programming languages have you messed around with? Java, C#, Python, Golang, Kotlin, C++, JavaScript
- What sort of tooling is on your machine?
  - Programming languages, compilers, runtimes etc Java, C#, JavaScript, Python, Golang, Kotlin,PHP, SQL, Oracle
  - What OS do you run? Windows 11
  - What editor/IDE do you use? Visual Studio editor, Maven, Gradle
- Are you more into front-end or back-end? (If you're
into web development). I am mostly into back-end development but since I am a full-stack developer, I am into front-end development at times.
- Are you interested in AI/ML, Systems Programming
or anything outside your current domain. Yes i am interested in AI/ML, Systems Programming and I am learning about Neural Networks Feedback Propagation algorithm on my own.
- What are you learning now? I am learning new technologies like Docker, MERN,etc.

## Let's hack!

Please answer in the language that you're
applying for. We're a JS shop, so answers in JS
get extra 🍪

- Find the longest word in a string.
  - Given `The quick brown fox jumped over the lazy dog` is the input to your function, it should return `jumped`.
var a="the quick browns fox jumped over the lazy dog";
var b=a.split(" ");
b.sort();
var min=100000000000000, max=0;
var temp="";
for(var i=0;i<b.length;i++){
  
    if(max<b[i].length){
      max=b[i].length;
      temp=b[i];
    }
  
}
console.log(temp);
- Repeat a string `n` times.
  - If `abc` and `3` are the arguments to your function, it shoudl return `abcabcabc`
var a="abc";
var n=3;
console.log(a.repeat(n));
- Remove duplicates in an array
  - If `[1, 20, 3, 1, 3, 3]` is the input to your
  function, it should return `[1, 20, 3]`
  
var a=[1,20,3,1,3,3];
console.log([...new Set(a)]);
- Remove falsy values
  - If `[42, "everything", "", 2, false, "everything"]` is the input to your function, it should return `[42, "everything", 2, "everything"]`
var array1 = [42, "everything", "", 2, false, "everything"];
 
var filtered = array1.filter(x => x);
console.log(filtered);
- Truncate a string
  - If `'Absolute victory'` and `3` are the inputs to
  your function, it should return `Abs...`
var a="Absolute victory";
var n=3,i=0;
var temp="";
for(var i=0;i<n;i++) {
  temp+=a[i];
}
console.log(temp);
## Notes

- We look for style and patterns when reviewing submissions.
- Please __do not__ lift answers from somewhere and
send it to us verbatim.
- Do show off your git kung-fu. Multiple commits? Branch naming?
- If you can't answer everything, thats ok too! Go ahead and raise that PR anyway.

> __வாழ்த்துகள்!__ 🙏
