# `twob || !twob`

Please put your responses in a file
called `answers.md`. And yes! our humor is dry 🏜

## Introductions

- Who are you? What do you like building? I am Vengatesh R., an U.D.C. (Administrative professional) as well as an Associate Tech Specialist and I like building and compiling programs and solving challenges and helping my friends in coding problems.
- Do you own a PC and have a good internet
 connection? Let's hear those specs 💪! Yes I have my own laptop by the brand manufacturer called Asus, it has Intel i5 Processor 10th generation, it has a graphics card called AMD Radeon, I have a good internet connection called TICFIBER, an optical fiber internet connection which delivers data at the maximum rate of 100 Mbps.  
- Your stackoverflow, linkedin, personal site.
https://www.linkedin.com/in/vengatesh-vishy-36212640/
Anything you'd want us to see.
- What programming languages have you messed around with? C++,Java,C#,Python,JavaScript,Golang, PHP, Kotlin
- What sort of tooling is on your machine? 
  - Programming languages, compilers, runtimes etc C#, Java, JavaScript, Python, C++, C,Kotlin, PHP, Golang, R, SQL, Oracle, Visual Studio Editor
  - What OS do you run? Windows 11
  - What editor/IDE do you use? Visual Studio Code Editor, Atom.io Editor, Maven, Gradle
- Are you more into front-end or back-end? (If you're
into web development).I am more into back-end development, but, since I am a full-stack developer, I am also into front-end development like React JS, Angular JS.
- Are you interested in AI/ML, Systems Programming
or anything outside your current domain? 
- What are you learning now? Yes I am interested in AI/ML, Systems Programming and I am learning about Flutter and XML Service-oriented programming.

## Let's hack!

Please answer in the language that you're
applying for. We're a JS shop, so answers in JS
get extra 🍪

- Find the longest word in a string.
  - Given `The quick brown fox jumped over the lazy dog` is the input to your function, it should return `jumped`.
var a= "The quick brown fox jumped over the lazy dog";
var b=a.split(" ")
var max=0,min=1000000000;
var i=0;
var temp="";
for(i=0;i<b.length;i++){
  if(max<b[i].length){
    max=b[i].length;
    temp=b[i];
  }
}
console.log(temp);
- Repeat a string `n` times.
  - If `abc` and `3` are the arguments to your function, it shoudl return `abcabcabc`
  var a="abc"
  var n=3
  console.log(a.repeat(n))

- Remove duplicates in an array
  - If `[1, 20, 3, 1, 3, 3]` is the input to your
  function, it should return `[1, 20, 3]`
  var a=[1,20,3,1,3,3]
  console.log(...new Set(a))

- Remove falsy values
  - If `[42, "everything", "", 2, false, "everything"]` is the input to your function, it should return `[42, "everything", 2, "everything"]`
var a=[42, "everything", "", 2, false, "everything"];
var filtered=a.filter(Boolean);
console.log(filtered);
- Truncate a string
  - If `'Absolute victory'` and `3` are the inputs to
  your function, it should return `Abs...`
var a="Absolute value";
var n=3;
var i=0;
var temp="";
for(i=0;i<n;i++){
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
