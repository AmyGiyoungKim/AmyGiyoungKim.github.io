---
title: "210215 넥사크로 SpringBoot 연동 & 댓글 수정 완료"
date: 2021-02-15 
categories: til nexacro springboot
---
### 💪 Things to do
(1) COMMENT MODIFY BY Ajax
- Got a troble to replace Textarea tag @ orginal contents
  - HOW TO SOLVE;
    - 'Modify Button' event should create Textarea tag right away (location : should be same place as 'Original Contents') 
     -  At this stage, 'Modify Button' should replace to 'Save Button'
    - Textarea tag will fill it up by writer & saved
    - Original Contents will updated
    
(2)NEXACRO
- Connection between SpringBoot and Nexacro was delayed due to Chrome 
  - PROBLEMS occur @ 'Base' folder & 'Frame' folder
  - PROBLEMS NOT occur @ 'FrameBase' folder 
  - ERORR looks like ;
    - Access to XMLHttpRequest at 'frame::rfmLeft.xfdl.js' from origin 'http://localhost' has index.html.1 been blocked by CORS policy:
  - SOLVED BY 'SHIFT + CTRL + R' OR '캐쉬비우기 그리고 강력 새로고침'  
  
### 💬 Leave Impression of your daily work
- Experiential knowledge will not forget
- Failure teaches success.

### 📢 Plan for tomorrow OR a week
-  Nexacro Front Page should be done till morning OR at least early afternoon.
