2024.12.25(수)

아래 영상을 따라 AI Chatbot의 HTML code를 작성해보았습니다. <br />
https://www.youtube.com/watch?v=B21G6tUI4L0&list=PLpwngcHZlPadhRwryAXw3mJWX5KH3T5L3&index=2

<br />[겪은 어려움]

'icon'이 아닌 'icon의 이름'이 button으로 출력됩니다.
![image](https://github.com/user-attachments/assets/e27a33e3-b819-4626-9939-92a10b87d209)

    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Material+Symbols+Rounded:opsz,wght,FILL,GRAD@24,400,0,0&icon_names=keyboard_arrow_down" />
    
            <button class="material-symbols-rounded">keyboard_arrow_down</button>
            
                    <button type="button"
                    class="material-symbols-rounded">sentiment_satisfied</button>
                    <button type="button"
                    class="material-symbols-rounded">attach_file</button>
                    <button type="submit"
                    class="material-symbols-rounded">arrow_upward</button>

<br />[해결]

href 속성으로 link된 url을 찬찬히 읽어보니 <br />
특정 icon이 연결되어 있어 <br />
해당 icon이 아닌 icon들은 출력되지 않았습니다.

icon을 특정하는 부분을 지워주고 family로 연결되도록 해놓으니 <br />
'icon의 이름'이 아닌 'icon'이 button으로 잘 출력됩니다.
![image](https://github.com/user-attachments/assets/03ef74c5-ffa1-468d-8e04-72bfec2bf633)
