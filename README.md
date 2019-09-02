
# CUI
| Name                   | URL                                                     | tag                                     |
| ---------------------- | ------------------------------------------------------- | --------------------------------------- |
| 날씨                    | curl v2.wttr.in/:help                                   | weather                                 |

# bookMark
| Name                   | URL                                                     | tag                                     |
| ---------------------- | ------------------------------------------------------- | --------------------------------------- |
| Test에 대한 고찰          | https://narusas.github.io/2018/04/30/Test.html          | test                                    |
| 不思議の国のSE用語         | https://qiita.com/t_nakayama0714/items/478a8ed3a9ae143ad854  | IT                                    |
| プロジェクトマネジャーが知るべき97のこと | https://プロジェクトマネジャーが知るべき97のこと.com | PM |

# program
| Name                   | URL                                                     | tag                                     |
| ---------------------- | ------------------------------------------------------- | --------------------------------------- |
| dbdiagram.io           | https://dbdiagram.io/home                               | database, diagram                       |
| frisby.js              | https://www.frisbyjs.com                                | test, rest api, javascript              |

# YouTube
| Name                   | URL                                                     | tag                                     |
| ---------------------- | ------------------------------------------------------- | --------------------------------------- |
| Caleb Curry            |  https://www.youtube.com/user/CalebTheVideoMaker2       | programming, tutorial                   |
| 오일석(기계학습)           | https://www.youtube.com/channel/UCMpRPu0OJjpoADoqhApEjrQ | machine learning                   |

#Java Memory
출처 : https://www.slideshare.net/JSUXDesign/java-82338809

## 기본형(byte)
| 타입     | 사이즈 | 최소값                 | 최대값                  |
| :------ | ---: | -------------------: | ---------------------: |
| boolean |    1 |                false |                   true |
| byte    |    1 |                 -128 |                    127 |
| char    |    2 |                    0 |                  65535 |
| short   |    2 |               -32768 |                  32767 |
| int     |    4 |          -2147483648 |             2147483647 |
| float   |    4 |             1.40E-45 |               3.40E+38 |
| long    |    8 | -9223372036854775808 |    9223372036854775807 |
| double  |    8 |             4.9E-324 | 1.7976931348623157E308 |


## 기본형의 래퍼클래스(byte)
| 타입       | 32bitJVM | 64bitJVM<br/>32GB미만 | 64bitJVM<br/>32GB이상 |
| :-------- | -------: | -------------------: | -------------------: |
| Boolean   |       16 |                   16 |                   24 |
| Byte      |       16 |                   16 |                   24 |
| Character |       16 |                   16 |                   24 |
| Short     |       16 |                   16 |                   24 |
| Integer   |       16 |                   16 |                   24 |
| Float     |       16 |                   16 |                   24 |
| Long      |       16 |                   24 |                   24 |
| Double    |       16 |                   24 |                   24 |

## 각종 오브젝트의 메모리 사용량
| 클래스 / 오브젝트                                  | 32bitJVM | 64bitJVM<br/>32GB미만 | 64bitJVM<br/>32GB이상 |
| :--------------------------------------------- | -------: | -------------------: | -------------------: |
| new String("https://[^/]+/") ※Java8            |       56 |                   72 |                   88 |
| new String("https://[^/]+/") ※Java9            |      N/A |                   56 |                   72 |
| "https://[^/]+/".toCharArray()                 |       40 |                   48 |                   56 |
| "https://[^/]+/".getBytes("UTF-8")             |       32 |                   32 |                   40 |
| Pattern.compile( "https://[^/]+/" )            |     1080 |                 1128 |                 1256 |
| new Date()                                     |       24 |                   24 |                   32 |
| new Timestamp()                                |       24 |                   32 |                   40 |
| Calendar.getInstance() ※GregorianCalendar      |      424 |                  448 |                  544 |
| ZonedDateTime.now()                            |       88 |                  120 |                  152 |
| LocalDateTime.now()                            |       48 |                   72 |                   80 |
| new SimpleDateFormat("yyyy-MM-dd HH:mm:ss.S" ) |     1232 |                 1296 |                 1880 |
| DateTimeFormatter.of("yyyy-MM-dd HH:mm:ss.S" ) |      432 |                  456 |                  704 |

## 구글 머신러닝 스터디잼 가이드라인
### 초급
https://docs.google.com/presentation/d/1B7Xsqw6pZei0E7PTvRw-c3mCPQnb3grm5JWMAtqlYhA/
### 중급
https://docs.google.com/presentation/d/1wogLNNAOhlzHmFe6GTurpV7evbNkiKY9A4LteIDgYcw
### 심화
https://docs.google.com/presentation/d/13Qn9wWMvwHtzoYjv3HGs9p6OR4vT3XRJbHlTrv0KASE
