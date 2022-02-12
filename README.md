Hyperbox is a symbolic execution virtual virtual machine for Waves RIDE smart-contracts, based on php, python and Z3Prover.
Demonstration version is available on http://2.59.42.98/hyperbox/
Architecture descripton: https://hsto.org/webt/jo/mj/5_/jomj5_tltmq3td9_r-xhyavhhqq.png

It mainly intended for formal verification and allows to find all existing vulnerabilities.

Hyperbox implements modern and powerful fully automatic multi-transactional search. For example, multi-transactional analysis support appeared in Mythril just recently: 
https://medium.com/consensys-diligence/the-tech-behind-mythx-smart-contract-security-analysis-32c849aedaef

Regular virtual machine is just a special case of symbolic VM, like cube is a special case of tesseract with 1 zero dimension. So Hyperbox can also be used as IDE for development and testing.

Current version is 0.1, so syntax limited with 
= + - * / % == != < <= > >= && ||

Created by Svyatoslav Yakimov. 
Telegramm: scp1001 
Waves donation adress (Current balance: 0) 3P5gNvDVRgRme8tVqtCaJzmSUSkjypr7cWe 

## Additional info

### Comment 1

A Habracomment https://habr.com/ru/post/450016/#comment_20093302 by S Yakimov https://habr.com/ru/users/scp1001/ . Its content has been copied & pasted below:

```
scp1001
30.04.2019 в 14:43 
Сегодня утром я выложил исходники на github в свободный доступ:
github.com/scp1001/hyperbox
Вся логика VM содержится в 2 файлах, hyperbox.php и hyperbox2.php
```
