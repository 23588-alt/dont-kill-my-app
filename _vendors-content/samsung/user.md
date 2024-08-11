---
manufacturer: samsung

---



## What optimization apps does Samsung have?

- **Android 13**: per-app battery optimization, Adaptive battery, Remove permissions, List of Alarms&Reminders, Adaptive power-saving, lists of Sleeping apps, Unused apps, Deep sleeping apps, Never sleeping apps
- **Android 11 + 12**: Battery optimization, Auto-optimize, Adaptive battery, Adaptive power-saving, Background restrictions, lists of Sleeping apps, Unused apps, Deep sleeping apps, Never sleeping apps
- **Android Pie and higher**: Device care, Background restrictions, lists of Sleeping apps, Unused apps, Auto-disable unused apps
- **Android Oreo and Nougat**: App power monitor, Background restrictions
- **Android Marshmallow or below**: Smart manager


1. [ Android 14 ](#android-14) 
2. [ Android 13 ](#android-13) 
2. [ Android 11 ](#android-11) <br>
3. [ Android Pie and 10 ](#android-pie-and-10) <br>
4. [ Android Oreo and Nougat ](#android-oreo-and-nougat) <br>
5. [ Android Marshmallow and older ](#android-marshmallow-and-older ) <br>



## Android 14

Not only does one need to toggle the system setting - but you can install additional Samsung "apps", and that will "most likely" let other apps run in the background.

### Good Guardians

Samsung developed an app named **Good Guardians**. This app is tightly integrated with the phone on a low level and has many modules. Any feedback about these features is welcomed.

* **Memory Guardian**: in the "Customize" tab of the module, there are two modes: "Default" and "Quick switching mode".
  
"Keep more apps in the background. When using the previously used app again, it is more likely to run with the last state of the app, not starting from the beginning."

* **Battery Guardian**: offers a few battery-saving controls, the option **App power saving** can close any app, if it uses an increased amount of battery (the system decides).

* **Galaxy app booster**: no information so far...

### Keep open

You can "lock" one app in the Recent apps to prevent it from being terminated.

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung_keep_open.jpg">
      </figure>

</div>

### Turning off the screen trick

If you want an app to keep running in the background when you turn off your phone's screen/lock your phone, then don't go to Home (Home screen) of your phone and then turn off the screen. Open the app and let it stay in the foreground, and only then turn off your screen/lock your phone. This might prevent the app from closing. When you unlock your phone, you will see that the app is running in the same state.


## Android 13

The settings are mostly the same as Android 11 below, with a few changes:

* The "Optimize battery usage" option doesn't exist anymore under "Special Access".
* Under "Device Care" there is no "Automation" or "Advanced" option anymore.
* Lock Recent App is not available.
* "Auto-optimize daily", "Adaptive power saving", and "Optimize battery usage" are not available

### Per-app battery optimizations

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_per_app_1.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_per_app_2.jpg">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_per_app_3.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_per_app_4.jpg">
      </figure>
      
</div>


### Adaptive battery

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_battery_1.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_battery_2.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_battery_3.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_battery_4.jpg">
      </figure>
      
</div>

### Remove permissions if app is unused

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_remove_permissions.png">
      </figure>

</div>



### List of "Alarms and Reminders"

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_alarms_1.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_alarms_2.jpg">
      </figure>
      
</div>


### Auto-optimizations

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_autooptimizations_1.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_autooptimizations_2.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_autooptimizations_3.jpg">
      </figure>
      
</div>

### Adaptive power saving

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_power_1.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_power_2.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_power_3.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_power_4.png">
      </figure>

   <figure>
    <img src="/assets/img/samsung/samsung13_adaptive_power_5.jpg">
      </figure>   
      
</div>

### Lists of Sleeping apps, Unused apps, Deep sleeping apps, Never sleeping apps

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung13_lists_1.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_lists_2.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_lists_3.png">
      </figure>

  <figure>
    <img src="/assets/img/samsung/samsung13_lists_4.jpg">
      </figure>
      
</div>

> The _"Put unused apps to sleep"_ option is the major headache we see on Samsung - a non-standard app-killing feature that isn't present in AOSP implemented only by Samsung which puts an app you did not use for X days to a mode with restricted background processing. On some releases, the period was as short as 3 days. So if you did not use your alarm clock over the weekend your alarm would not ring.



## Android 11

On Android 11 Samsung will prevent apps work in the background by default unless you exclude apps from battery optimizations. This is a severe divergence from standard Android process management policies.<br>
Yes, this is a long way to go! Devs cannot ask for it automatically as they risk being kicked out from the Play Store due to policy violations.

### Lock the app in Recent

1. Open Recent apps.<br>
2. Find Your app.<br>
3. Long-press the icon of the app.<br>


### Battery optimization

To keep your apps working properly make sure you enable:<br>
_Settings -> Apps -> Your App -> Battery -> Battery optimization -> All apps -> Your app -> Don't optimize_.<br>

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung1.png">
    <figcaption>Settings -> Apps, then select Your app</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/samsung3.png">
    <figcaption>Your app -> Battery</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/samsung4.png">
    <figcaption>Battery -> Battery optimization</figcaption>
  </figure>

</div>

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/samsung5.png">
    <figcaption>Settings -> Switch to All apps listing</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/samsung6.png">
    <figcaption>Find Your app<br> switch off the battery optimization</figcaption>
  </figure>

</div>


### Optimize battery usage

*Settings > Apps* > (⁝) *menu > Special Access > Optimize battery usage*

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/s10_obu_1.png">
    <figcaption>1. Open Apps section.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_obu_2.png">
    <figcaption>2. Tap on the (⁝) menu.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_obu_3.png">
    <figcaption>3. Choose Special Access.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_obu_4.png">
    <figcaption>4. Open Optimiza battery usage.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_obu_5.png">
    <figcaption>5. Expand the list to All apps.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_obu_6.png">
    <figcaption>6. Toggle the apps.</figcaption>
  </figure>

</div>


### Auto-optimize daily + Adaptive power saving

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/s10_battery_1.png">
    <figcaption>1. Open Battery > (⁝) menu.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_battery_2.png">
    <figcaption>2. Choose Automation.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_battery_3.png">
    <figcaption>3. Adjust.</figcaption>
  </figure>

</div>

On some phones the route differs:

<div class="img-block">
 <figure>
    <img src="/assets/img/samsung/s9_7.png">
    <figcaption>1. <strong>Device care</strong><br> and tap the 3-dot menu. </figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s9_8.png">
    <figcaption>2. Tap on <strong>Advanced</strong>. </figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s9_9.png">
    <figcaption>3. Disable <strong>Auto-optimization</strong>. </figcaption>
  </figure>

</div>

### Adaptive battery

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/s10_ab_1.jpg">
    <figcaption>1. Open Battery -> More battery settings.</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_ab_2.png">
    <figcaption>2. Disable Adaptive battery.</figcaption>
  </figure>

</div>

### Lists of Sleeping apps, Unused apps, Deep sleeping apps, Never sleeping apps

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/S10_sleeping_10.jpg">
    <figcaption>1. Open Battery > Background usage limits. </figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/S10_sleeping_2.png">
    <figcaption>2. Check the lists.</figcaption>
  </figure>

</div>

<div class="caution-box">Warning: Make sure <strong>Put unused apps to sleep</strong> is disabled. Otherwise, Samsung will put your apps back to sleep after a few days (3 by default) even if you have woken them up manually!</div>


## Android Pie and 10

Battery optimizations are *turned on by default*. It is possible the disabled restrictions might get revert after OS update or reboot.
By default any app which is not started in 3 days is put to sleep and background tasks including alarms will stop working.

### Put unused apps to sleep

_Phone settings -> Device care -> Tap on the Battery item_ -> (⁝) _3-dot menu > Settings_
<br>
Uncheck Your app from this list.

### Auto-disable unused apps

_Phone settings -> Device care -> Tap on the Battery item_ -> (⁝) _3-dot menu > Settings_
<br>
Uncheck Your app from this list.

### Background restrictions

Check that _Phone settings -> Apps -> Sleep as Android -> Battery -> Background restriction_ state as **App can use battery in background** for the apps you need to run in the background.

### Sleeping apps

Sleeping apps menu is the sniper's nest for Samsung's app killing policies. Make sure to follow the instructions very carefully to prevent the apps from being killed.

<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/s10_1.jpg">
    <figcaption>1. Start <strong>Device care</strong><br>from phone settings</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_2.jpg">
    <figcaption>2. Tap Battery</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_3.jpg">
    <figcaption>3. Tap the 3-dot menu > Settings</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_5.jpg">
    <figcaption>4. Disable all toggles<br>(except Notifications)</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_6.jpg">
    <figcaption>5. Tap "Sleeping apps"</figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s10_8.jpg">
    <figcaption>6. Wake up all the apps<br>using the trashcan icon</figcaption>
  </figure>

</div>

On some phones, the layout may differ:


<div class="img-block">
  <figure>
    <img src="/assets/img/samsung/s9_1.png">
    <figcaption>1. Start <strong>Device care</strong><br>from phone settings. </figcaption>
  </figure>

  <figure>
    <img src="/assets/img/samsung/s9_2.png">
    <figcaption>2. Tap <strong>Battery</strong>. </figcaption>
  </figure>

   <figure>
       <img src="/assets/img/samsung/s9_3.png">
       <figcaption>3. Open <strong>App power management</strong>. </figcaption>
     </figure>

   <figure>
       <img src="/assets/img/samsung/s9_4.png">
       <figcaption>4. Disable the option <br><strong>Put unused apps to Sleep </strong>. </figcaption>
     </figure>

   <figure>
       <img src="/assets/img/samsung/s9_5.png">
       <figcaption>5. Remove your app from<br> the lists in <strong>Sleeping apps</strong><br>and <strong>Deep sleeping apps</strong>. </figcaption>
     </figure>

   <figure>
       <img src="/assets/img/samsung/s9_6.png">
       <figcaption>6. Add you app to the list<br> in <strong>Apps that won't be put to sleep</strong>. </figcaption>
     </figure>

</div>


<div class="caution-box">Warning: Make sure <strong>Put unused apps to sleep</strong> and <strong>Auto-disable unused apps</strong> is disabled. Otherwise, Samsung will put your apps back to sleep after a few days (3 by default) even if you have woken them up manually!</div>

### Game Boosting features

Samsung optimizing features that monitor your phone usage and can alter your settings. Although such feature might be useful, in some cases you don't wish to loose all background processed. This can results in termination of background processes when you play games (for example blue light filter apps will stop, or notification are delayed).
<br>
There are Game Booster app, Game optimizing service, and Game Launcher.
<br>


1. Go to Apps and then click the Samsung app settings. Scroll to the Game Booster.<br>
2.尽量关掉。然后单击“游戏期间阻止”并关闭所有内容。<溴>
3.接下来，在应用程序中，找到游戏优化服务-该服务无法禁用，但您可以移除所有权限。<溴>
4.最后，再次搜索应用程序并找到游戏启动器。您可以移除权限，然后将其禁用。<溴>

<div班级="img-block">
  <数字>
    <IMGsrc="/assets/img/samsung/game_superor_1.jpg">
    <figcaption>1.打开三星应用程序设置。</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/samsung/game_superor_2.jpg">
    <figcaption>2.找到游戏助推器应用。</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/samsung/game_booster.jpg">
    <figcaption>3、关闭所有选项。</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/samsung/game_booster_4.JPG">
    <figcaption>4.在三星应用程序设置中找到游戏优化。</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/samsung/game_superor_5.jpg">
    <figcaption>5.删除其所有权限。</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/samsung/game_superor_3.jpg">
    <figcaption>6.找到游戏启动器并将其禁用。</figcaption>
  </数字>

</div>


###优化电池使用
电池优化隐藏在每个应用程序的设置部分。若要禁用该应用程序的优化，您需要展开子菜单，这样列表将显示受限制的应用程序。
打开_系统设置->应用程序->您的应用程序->优化电池使用_，展开列表，然后使用切换将应用程序设置为“未优化”。

<div班级="img-block">
  <数字>
    <IMGsrc="/assets/img/samsung/battery_optimization_9.jpg">
    <figcaption>1.优化电池使用。</figcaption>
  </数字>

  <数字>
    <IMGsrc="/assets/img/samsung/battery_optimization_9.jpg">
    <figcaption>2.展开列表。</figcaption>
  </数字>

</div>

##安卓奥利奥和牛轧糖8+7

随着Galaxy S8的推出(以及一些早期的实验)，三星推出了一种延长电池寿命的尝试，名为<强大的>app电源监控</强大的>.<溴>

###app电源监控

可完全关闭应用程序电源监控，也可单独管理应用程序。<溴>
要使应用程序在后台正常工作，您需要将它们列入_app电源监控_并将它们添加到<强大的>未受监控的应用程序</强大的>:<溴>
<溴>
打开_设置->设备维护->电池_，在底部，您将看到您最常用的应用程序列表。<溴>
正在休眠的应用程序将显示在<强大的>休眠应用程序</强大的>列表位于底部(点击可展开列表)。<溴>
列表<强大的>未受监控的应用程序</强大的>位于最底部(需要更长的滚动时间)-这些是您特别希望排除(白名单)的应用程序*app电源监控*邪恶的触角。<溴>
当在内部_未受监控的应用程序_菜单，您可点击3点菜单从列表中添加或删除应用程序。<溴>

##Android Marshmallow及以下版本

在其他三星手机上，路径可能如下所示：<溴>

*电话设置>应用程序>选择三点菜单(右上角)>特殊访问>优化电池使用>*在列表中查找您的应用程序，并确保未选中该应用程序。

>注意：如果您为应用程序启用“侧屏照明”，应用程序将无法唤醒您的屏幕。若要允许应用程序唤醒屏幕，请将其从侧屏照明应用程序列表中移除。

