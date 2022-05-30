# WinUI 3 를 활용한 다국어 응용프로그램

# Project명 📂

WinUI 3 를 활용한 다국어 응용프로그램

Multilingual Application using WinUI3

# Visual Studio Settings ⚙️

1. [VS를 깔자](https://docs.microsoft.com/en-us/visualstudio/releases/2022/release-notes)
2. 다음과 같은 개발 키트를 설치하자
- 워크로드
    - .NET
    - Desktop Dev with C++
    - Universal Windows Platform development
- 개별 컴포넌트들
    - Windows 10 SDK (10.0.19041.0)
    - Installation details에서...
        - Universal Windows Platform development
            - C++ (v142)
1. SDK를 설치해준다.

<aside>
💡 On Visual Studio 2022 version 17.1 or later, you DON'T need to install Windows App SDK Visual Studio extension (VSIX). Instead, you need to select:

"Windows App SDK C# Templates" on .NET Desktop Development for C#
"Windows App SDK C++ Templates" on Desktop development with C++

</aside>

![Untitled](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/f4c2843b-7e2a-4b4e-839f-0fda977fd7d1/Untitled.png)

1. VS를 실행하자. *이 때, General이 아닌 Visual C#으로 세팅해준다*
- 만약 놓쳤다면 아래를 참고해보자!
    
    [https://docs.microsoft.com/en-us/visualstudio/ide/environment-settings?view=vs-2022](https://docs.microsoft.com/en-us/visualstudio/ide/environment-settings?view=vs-2022)
    

## WinUI 3 Settings ⚙️

[Template Studio for WinUI (C#)을 설치](https://marketplace.visualstudio.com/items?itemName=TemplateStudio.TemplateStudioForWinUICs)해준다.

## ****Multilingual App Toolkit 4.0 Editor**** 🛠️

[Multilingual App Toolkit 4.0 Editor 설치](https://docs.microsoft.com/en-us/windows/apps/design/globalizing/multilingual-app-toolkit-editor-downloads)해준다.

# Process 📜

1. "Multilingual App Toolkit Editor" app 설치 
2. "Multilingual App Toolkit v4.1 (VS 2022+)" extension 설치
3. Template Studio를 사용하여 WinUI 3 app 생성
4. "Resources.rews"와의 “Strings” 폴더 생성
5. "Resources.rews"를 편집하기 
6. 이 프로젝트에 대해 "Multilingual App Toolkit" 사용
7. 번역파일인 (MultilingualResources / *.xlf files) 추가하기
8. "Multilingual App Toolkit Editor"을 사용하여 번역하기
9. 언어 변경 기능 구현 
10. LocalizationService class 선언 및 정의
11. ResourceManager class 선언 및 정의
12. 가능한 언어의 목록 생성
13. Windows.Globalization.ApplicationLanguages.PrimaryLanguageOverride 코딩
14. UI (SettingsViewModel.cs) 구현
15. UI (SettingsPage.xaml) 구현

# Reference 🔖

**Install Visual Studio 2022 (Ver.17.0) and create your first WinUI 3 app | Tutorial**

- [https://www.youtube.com/watch?v=zRqj2Bt_GjY](https://www.youtube.com/watch?v=zRqj2Bt_GjY)
- https://github.com/AndrewKeepCoding/LocalizationSampleApp

**Install VS**

- [https://docs.microsoft.com/en-us/visualstudio/releases/2022/release-notes](https://docs.microsoft.com/en-us/visualstudio/releases/2022/release-notes)

**WinUI 3 | Localization | Multilingual App Toolkit Editor | WinAppSDK | XAML | Tutorial | C# | .NET**

- [https://www.youtube.com/watch?v=prOj1j1OILU](https://www.youtube.com/watch?v=prOj1j1OILU)

****Template Studio****

- https://github.com/microsoft/TemplateStudio

****Multilingual App Toolkit 4.0 Editor****

- [https://docs.microsoft.com/en-us/windows/apps/design/globalizing/multilingual-app-toolkit-editor-downloads](https://docs.microsoft.com/en-us/windows/apps/design/globalizing/multilingual-app-toolkit-editor-downloads)