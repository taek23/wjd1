# 리눅스 명령어
---
## top: 실시간으로 프로세스의 CPU 사용률 알려주는 명령어. 5초 간격으로 업데이트하여 화면에 출력한다. 


|옵션|내용|
|:---:|---|
|-b| 배치모드로 정보를 출력합니다. 실시간 상화 대화형모드로 정보를 화면에 일렬로 출력합니다.|
|d delay| 지정한 시간(delay 초)의 간격으로 정보를 업데이트하여 출력합니다.|
|-i| idle	토글값이 off일 때, idle 프로세스나 좀비 프로세스 정보를 출력하지 않습니다.|
|-n| num	지정한 시간(num)만큼 업데이트 정보를 출력합니다.|
|-p| pid	지정한 프로세스 ID(pid)의 정보만을 출력합니다.|
|-q| 시간의 간격 없이 계속하여 업데이트 정보를 출력합니다.|
|-s|	몇 개의 대화식 명령을 비활성화 합니다.|
|-S|	누적된 정보를 출력합니다.|


---

## ps: 현재 실행중인 프로세스 목록과 상태를 보여주는 명령어
|옵션|내용|
|:---:|---|
|-e| 실행중인 모든 프로세스의 정보를 출력한다.|
|-f| 프로세스에 대한 자세한 정보룰 출력한다.|
|-u [사용자이름]| 특정 사용자에 대한 모든 프로세스의 정보를 출력|
|-p pid| pid로 지정한 프로세스의 정보를 출력|
|u| 프로세스 소유자의 이름, CPU 사용량, 메모리 사용량 등 상세 정보를 출력|
|a| 터미널에서 실행한 프로세스의 정보를 출력|
|x| 실행 중인 모든 프로세스의 정보를 출력|

---            

 ## jobs: 작업이 중지된 프로세스나 백그라운드로 실행 중인 프로세스 상태를 표시.
|옵션|내용|
|:---:|---|
|-l| 프로세스 그룹 ID를 state 필드 앞에 출력|
|-n| 프로세스 그룹 중에 대표 프로세스 ID를 출력|
|-p| 각 프로세스 ID에 대해 한 행씩 출력|
|command| 지정한 명령어를 실행|
           
---

 ## kill:프로세스에 특정한 signal을 보내는 명령어. 일반적으로 종료되지 않는 프로세스를 종료 시킬 때 많이 사용한다.
|옵션|내용|
|:---:|---|
|kill –9 <pid>| 해당 pid의 프로세스를 강제 종료|

 ※ ps -ef 명령어를 grep하여 특정 프로세스의 PID를 찾을 수 있습니다.

---

# vim 메크로 사용법
 
1. 매크로 시작 = q[name] 

2. .... (매크로 입력)

3. 매크로 종료 = q

4. 매크로 실행 = @[name]

5. 매크로 여러번 실행 = [number]@[name]

