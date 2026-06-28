# DataEditorX
[YGOPro](https://github.com/Fluorohydride/ygopro)의 카드 데이터베이스(.cdb) 편집기입니다.

## 다운로드
https://github.com/Ice-Pendragon/DataEditorX/raw/refs/heads/DataEditorX-Korean/win32/win32.zip   

> **Q&A**   
Q: 프로그램이 실행되지 않아요..   
A: [.NET Framework](https://dotnet.microsoft.com/en-us/download/dotnet-framework/net48)를 설치하세요.

## 기능
* 카드 데이터베이스를 만들거나 편집할 수 있습니다.
* 카드 데이터베이스를 서로 비교하고, 카드들을 간편하게 복사 & 붙여넣기할 수 있습니다.
* YGOPro 덱 파일(.ydk) 및 카드 이미지 폴더(YGOPro의 /pics/ 폴더 등)을 불러들일 수 있습니다.  
* 카드의 스크립트 코드(.lua)를 만들거나 편집할 수 있습니다.  
* [Magic Set Editor 2](https://github.com/247321453/MagicSetEditor2) 세트를 가져오거나 내보낼 수 있습니다.   
...

> **Q&A**   
Q: 새로운 카드군은 어떻게 추가하나요?  
A: 우선, 새로운 카드군의 카드군 번호 (16진수 숫자) 를 결정하세요. 기존의 카드군 번호들과 동일하면 안 됩니다. 그 뒤에 카드군 목록 오른쪽의 글상자에 그 숫자를 기입하세요.  
새로운 카드군의 이름이 카드군 목록에 나타나게 하고 싶다면, /data/cardinfo_xxx.txt (xxx는 언어 이름) 을 열어서, "##setname" 과 "#end" 사이에 새로운 줄을 추가하고, 카드군 번호 (맨 앞에 0x를 덧붙입니다) 뒤에 탭을 하나 넣은 뒤, 카드군 이름을 기입해 주세요.

## 언어 설정
메뉴에서 도움말 --> 언어를 선택하세요.
당신이 언어 파일을 직접 추가하고 싶다면, 두 개의 파일을 만들어야 합니다:    
>/data/language_xxx.txt (메뉴 및 UI)   
/data/cardinfo_xxx.txt (카드 정보)    

language_english.txt 및 cardinfo_english.txt 의 각 라인은 탭으로 분리되어 있습니다. **(빈칸이 아닙니다!)**  
탭 오른쪽의 내용을 원하는 언어로 번역한 뒤, language_xxx.txt 및 cardinfo_xxx.txt 로 저장하세요.
