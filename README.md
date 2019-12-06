# Markdown表情库
:green_heart:` 链接`(https://www.webfx.com/tools/emoji-cheat-sheet/)

---
:bowtie:
:smile:
:laughing:
:blush:
:smiley:
:relaxed:
:smirk:
:heart_eyes:
:kissing_heart:
:kissing_closed_eyes:
:flushed:
:relieved:
:satisfied:
:grin:
:wink:
:stuck_out_tongue_winking_eye:
:stuck_out_tongue_closed_eyes:
:grinning:
:kissing:
:kissing_smiling_eyes:
:stuck_out_tongue:
:sleeping:
:worried:
:frowning:
:anguished:
:open_mouth:
:grimacing:
:confused:
:hushed:
:expressionless:
:unamused:
:sweat_smile:
:sweat:
:disappointed_relieved:
:weary:
:pensive:
:disappointed:
:confounded:
:fearful:
:cold_sweat:
:persevere:
:cry:
:sob:
:joy:
:astonished:
:scream:
:neckbeard:
:tired_face:
:angry:
:rage:
:triumph:
:sleepy:
:yum:
:mask:
:sunglasses:
:dizzy_face:
:imp:
:smiling_imp:
:neutral_face:
:no_mouth:
:innocent:
:alien:
:yellow_heart:
:blue_heart:
:purple_heart:
:heart:
:green_heart:
:broken_heart:
:heartbeat:
:heartpulse:
:two_hearts:
:revolving_hearts:
:cupid:
:sparkling_heart:
:sparkles:
:star:
:star2:
:dizzy:
:boom:
:collision:
:anger:
:exclamation:
:question:
:grey_exclamation:
:grey_question:
:zzz:
:dash:
:sweat_drops:
:notes:
:musical_note:
:fire:
:hankey:
:poop:
:shit:

---
![hello](https://images.pexels.com/photos/3224156/pexels-photo-3224156.jpeg?cs=srgb&dl=photo-of-mountain-during-dawn-3224156.jpg&fm=jpg)
---

![PICTURE](https://maven.apache.org/images/apache-maven-project.png)
# Maven常见问题与解决方案
|问题|解决了吗？|
|---|---|
|一|yes|
|:broken_heart:
:heartbeat:
:heartpulse:
:two_hearts:
:revolving_hearts:
:cupid:|
># 问题1   
[ERROR] The goal you specified requires a project to execute but there is no POM in this directory (D:\myapplication). Please verify you invoked Maven from the correct directory. -> [Help 1]
[ERROR]
[ERROR] To see the full stack trace of the errors, re-run Maven with the -e switch.
[ERROR] Re-run Maven using the -X switch to enable full debug logging.
[ERROR]
[ERROR] For more information about the errors and possible solutions, please read the following articles:
[ERROR] [Help 1] http://cwiki.apache.org/confluence/display/MAVEN/MissingProjectException<br/>
# 解决办法来源   
:point_right: https://www.cnblogs.com/zhexuejun/p/11525623.html
--------------------------------------------------------------
# 解决办法

># 给命令的参数+双引号   
>mvn install:install-file "-DgroupId=li" "-DartifactId=hutool-all" "-Dversion=5.0.7" "-Dfile=hutool-all-5.0.7.jar" "-Dpackaging=jar"  


