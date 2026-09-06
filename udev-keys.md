# udev 키

| 키 | 의미 |
|---|---|
| SUBSYSTEM | 장치가 속하는 서브시스템 |
| KERNEL | 커널 장치 이름 패턴 |
| ATTR{loop/backing_file} | 해당 loop 장치의 backing 파일 |
| SYMLINK+= | /dev 아래 별칭 목록에 추가 |
| MODE | 장치 파일 접근 권한 |
| GROUP | 장치 소유 그룹 |

`==`는 비교, `=`는 할당, `+=`는 목록에 추가한다.
USB 부모 속성은 `ATTRS{idVendor}`와 `ATTRS{idProduct}`로 함께 비교한다.
