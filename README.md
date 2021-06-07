# 2021 1학기 오픈소스SW 프로젝트

## *Participant*

김후정 (팀장) : https://github.com/gnwjd309

권민구 : https://github.com/kwon-mingoo-3596

신은진 : https://github.com/eunjins

---
## *Introduce*

*본 프로젝트는 2021년도 1학기 오픈소스SW 프로젝트 수업에서 진행한 프로젝트 입니다.*

우리는 모바일 애플리케이션을 사용하여 다양한 컨텐츠를 즐길 수 있습니다. 하지만 텍스트를 읽기에 독해력이 부족한 사람들, 또는 저시력자나 신체적인 어려움이 있는 사람들은 일반인들처럼 자유롭게 사용하는 것이 어려울 수 있습니다.

이러한 점을 개선하고자, 모든 사람들이 사용할 수 있는 **모바일 텍스트 뷰어 애플리케이션**을 제작하게 되었습니다.

해당 애플리케이션은 다양한 기능을 제공합니다.

* 시선 추적 : 사용자의 시선을 기반으로 애플리케이션의 전반을 제어할 수 있습니다.
* TTS : 바쁜 상황이거나, 눈으로 컨텐츠를 읽는 것이 불가능할 때 해당 텍스트를 음성으로 서비스합니다.
* STT : 애플리케이션을 눈으로 확인할 수 없을 때, 음성으로 애플리케이션을 제어할 수 있습니다.  
        (현재는 간단한 명령어, 읽기 및 요약 등이 가능합니다.)
* OCR : 직접 사진을 찍어 업로드 하는 기능을 제공합니다.
* 감성 분석 : 애플리케이션 내의 텍스트 전반의 성격을 파악할 수 있도록 감성 분석 결과를 제공합니다.
* 요약 및 키워드 제공 : 애플리케이션 내의 텍스트를 요약하고 키워드를 추출함으로써, 사용자의 이해를 도울 수 있습니다.

추후에는 더욱 다양한 파일 형식을 제공할 예정이며, 전반적인 애플리케이션의 개선에 힘쓰고자 합니다.

---
## *How to use*

*본 프로젝트의 서버는 Microsoft의 Azure에서 구축하였습니다.* 

1. model 디렉터리 안에 tts 모델 파일을 추가합니다.
2. app.py를 실행합니다.
3. 안드로이드 애플리케이션을 실행합니다.  
   (애플리케이션과 관련된 사항은 해당 <a href="https://github.com/gnwjd309/OSSW-Project" target="_blank">링크</a>를 참고해 주세요.)

---
## *Struct*

애플리케이션과 서버의 전체적인 구조 입니다.

![](https://github.com/gnwjd309/OSSW-Project/blob/main/readme_source.PNG)

---
## *Used Library*
- Kosac : http://word.snu.ac.kr/kosac/
- SCE-TTS : https://github.com/sce-tts/sce-tts.github.io
- Tesseract Data v4.0 :  https://github.com/tesseract-ocr/tessdata/releases/tag/4.0.0
