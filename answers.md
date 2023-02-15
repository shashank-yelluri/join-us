## Introductions

1. **Who are you? What do you like building?** 
- I am a Full Stack Developer and my name is Shashank Y. I've completed my graduation in Computer Science and Spec in BioInformatics with an overall CGPA of 9.02 from VIT vellore. I've also got work experience from two different styles of companies one being ICICI( Biggest Organisation ) and the latter one is Prodigal( StartUp ). 
- I love to build websites with crazy architectures. I always try to include all my learnings to build something.

2. **Do you own a PC and have a good internet connection? Let's hear those specs 💪!**
- Yes, I do own a MacBook Pro which is of 8 GB Ram and 512 GB Memory. I do not play any games, so i do not see any problems with it's performance even after having some couple of containers running in Docker.

3. **Your stackoverflow, linkedin, personal site. Anything you'd want us to see.**
- Linkedin - https://www.linkedin.com/in/shashank-yelluri-4aa082238/
- GitHub - https://github.com/shashank-yelluri

4. **What programming languages have you messed around with?**
- I always loved learning new tech stacks, so as per your question i've messed up with a lot of programming languages,
- Python
- JavaScript
- JAVA
- GoLang
- PHP

5. **What sort of tooling is on your machine?**
   1. **Programming languages, compilers, runtimes etc**
   - I've setup for all the above mentioned Programming Languages. 
   
   2. **What OS do you run?**
   - Mac OS
   
   3. **What editor/IDE do you use?**
   - VS Code

6. **Are you more into front-end or back-end? (If you're into web development).**
- Slightly more into Backend.

7. **Are you interested in AI/ML, Systems Programming or anything outside your current domain.**
- Yes. The domain mentioned in the question is what i love to do apart from my domain. I've also built some ML models and integrated that model with the website that i built using python django framework.

8. **What are you learning now?**
- Currently i am more into Next.js which i found interesting in terms of SEO and also kind of similar to the technology that i've already worked on (React JS).



## Let's hack!

1. **Find the longest word in a string.**
```
// Given The quick brown fox jumped over the lazy dog is the input to your function, it should return jumped.

const findMaxLengthWord = (sentence) => {
    let maxWordLength = 0;
    let result = "";
    for (let word of sentence.split(" ")) {
        if (word.length > maxWordLength) {
            maxWordLength = word.length;
            result = word;
        }
    }
    
    return result;
}
```

2. **Repeat a string n times.**
```
// If abc and 3 are the arguments to your function, it shoudl return abcabcabc

const repeatWord = (word, noOfTimes) => {
    return word.repeat(noOfTimes);
}
```

3. **Remove duplicates in an array**
```
// If [1, 20, 3, 1, 3, 3] is the input to your function, it should return [1, 20, 3]

const removeDuplicates = (numbersArray) => {
    return [...new Set(numbersArray)];
}
```

4. **Remove falsy values**
```
// If [42, "everything", "", 2, false, "everything"] is the input to your function, it should return [42, "everything", 2, "everything"]

const filterFalsyValues = (valuesArray) => {
    return arr.filter(value => value);
}
```

5. **Truncate a string**
```
// If 'Absolute victory' and 3 are the inputs to your function, it should return Abs...
// Note: Assuming that 3 dots are also resemblence of the input 3. (May be i am overthinking, but implementing it for the safer side.)

const truncateString = (word, trimLength) => {
    return `${word.substring(0, trimLength)}${'.'.repeat(trimLength)}`;
}
```




