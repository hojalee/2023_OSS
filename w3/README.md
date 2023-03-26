# 2023_OSS
## 2023 OSS 수업
-----
### 3주차 git
### 이미지
![Alt text](/img/kau/kau.png)
### 링크
[LMS](https://lms.kau.ac.kr/login.php)
#### ProGit 링크
[ProGit](https://git-scm.com/book/ko/v2)
-----
###2주차 숙제
'''bash
echo "----------"
echo "name :"
echo "이호준"
echo ""
echo "----------"
echo "student id :"
echo "2020125055"
echo "----------"
echo ""
echo "file path :"
find /home/kau2 -name "w2_homework.txt" 2> /dev/null
echo ""
echo "----------"
echo "line number :"
path=$(find /home/kau2 -name "w2_homework.txt" 2> /dev/null)
cat $path | wc -l | cut -c 1
echo ""
echo "----------"
echo "last line :"
cat $path | tail -n 1
'''
