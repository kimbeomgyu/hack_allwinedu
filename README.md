# hack_allwinedu

## 사용방법
1. allwinedu.net에 로그인
2. 개발자 도구(F12)를 열고 콘솔(Console) 탭으로 이동
3. 아래 코드 중 user_id와 lecture_items를 필요에 맞게 수정
3-1. user_id는 로그인한 ID (이름+생일) ex. 홍길동0123
3-2. lecture_items는 강의 목록 (필요한 강의만 남겨두고 나머지는 지워서 쓰세요)
4. 콘솔에 복사 붙여넣기 후 엔터

## 주의사항
이 프로그램을 사용함으로써 발생하는 모든 문제의 책임은 사용자 본인에게 있습니다.
사용자는 이 프로그램을 사용함으로써 발생하는 모든 문제에 대해 제작자에게 책임을 묻지 않습니다.

## 참고
1. lecture_items.time 값은 수강해야하는 "남은 시간"입니다. 중간부터 수강하려면 시간을 수정해주세요.
2. 코드 실행을 멈추려면 콘솔을 새로고침하면 됩니다.
3. 강의를 수강하면서 다른 작업을 하면 안됩니다. (콘솔을 닫으면 안됩니다.)
4. 만일 스크립트로 실행하려면 쿠키값을 직접 넣어줘야합니다. (user_session)
4-1. 쿠키값은 로그인 후 개발자 도구(F12) Script 탭에 들어가서 `document.cookie.match(/ASPSESSIONIDQWWQASCD=([^;]*)/)[1]` 를 실행하면 나옵니다.