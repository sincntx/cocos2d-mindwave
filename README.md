# cocos2d-mindwave

This project show that Cocos2d-x connect MindWave Mobile.

# Get Started

1. Create a cocos2d-x project(JS).

2. Add a 'thinkgear.js' in your cocos2d-x project(ex : /src).

3. Find a android project in your cocos2d-x project(ex : frameworks/runtime-src/proj.android or proj.android-studio).

4. Add 'ThinkGear.jar'(Download at http://neurosky.com/) in your android project.

5. Add 'ThinkGear.java' in your android project.

6. Modify 'AppActivity.java' in your android project.

7. Use the code.

ex : in /main.js

cc.thinkgear = new cc.ThinkGear();
cc.thinkgear.connect();
