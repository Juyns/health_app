# Health App Project

## Description
	* ### 웨이트 트레이닝의 루틴, 세부 운동의 중량이나 반복횟수 등의 관리에 이용되는 API서버입니다.


***
## 
## 

## usage
 * 사용자는 루틴을 추가하고, 그 후 세부적인 workout들을 추가할 수 있습니다.
 
 * 모든 workout들은 루틴을 참조하기에 특정 루틴을 삭제할 시 하위 요소인 workout들 또한 삭제됩니다.
 
 * 모든 루틴에 해당 view와 일별 루틴에 대한 view, 그리고 루틴 별 세부 view가 제공됩니다.
 
 * 루틴과 워크아웃에 대한 detailed view는 수정 및 삭제를 지원합니다.
 
 * 루틴과 워크아웃의 추가는 각각 routine, workout에 대한 overall view에서 지원됩니다.
 
 * 루틴의 완수는 routine table의 done, completed 두 가지로 분류됩니다.
    * done은 일일 완수 여부를 지정하며, DayStart 의 get메서드 실행으로 일일 단위로 초기화될 수 있습니다.
    * completed는 루틴의 종료일이 지난 시점 완수 여부를 지정합니다.
    

***
## 
## 
## Prerequisite
* requirements
  * asgiref==3.3.1
  * certifi==2020.12.5
  * cffi==1.14.4
  * chardet==4.0.0
  * cryptography==3.3.1
  * defusedxml==0.6.0
  * Django==3.1.6
  * django-allauth==0.44.0
  * django-rest-auth==0.9.5
  * djangorestframework==3.12.2
  * idna==2.10
  * oauthlib==3.1.0
  * pycparser==2.20
  * PyJWT==2.0.1
  * python3-openid==3.2.0
  * pytz==2021.1
  * requests==2.25.1
  * requests-oauthlib==1.3.0
  * six==1.15.0
  * sqlparse==0.4.1
  * urllib3==1.26.3


## 자세한 API명세 및 예시는 https://documenter.getpostman.com/view/14363970/TzY4hG9w  참조
