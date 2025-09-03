# MajorDiscipline
Major Discipline is an extension of [Semantic Versioning](https://github.com/semver/semver) which seeks to further reduce the problems of code death and zombie vulnerability.

### Code Death
Code death is simply when a specific major version is no longer the latest. Likely, the version will stop receiving updates. It is no longer living. If a flaw is discoverd, you're stuck with it. Major Disciplin seeks to reduce the frequency of code death by reducing the frequency of major versions. 

### Zombie Vulnerability
Often times (Though I can't remember any off the top of my head, if you can remember, let me know in "Issues"), software A will depend on a specific major version of software B. Then as time goes on, a vulnerability is found and patched in a later version fo software B. Unfortunatly, software A never updated because the older version "just worked" and replacing it "would be too much of a hassle". This is a **zombie vulnerability**. The purpose of Major Discipline is to reduce the hassle of adopting newer major versions by reducing the frequency of major versions as well as providing easily followed upgrade instructions (for things like replacing deprecated functions).  
