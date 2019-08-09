---
Title: Lua Scripting for Animations
Sort: 4
ShowOnHome: true
---
### Learn Lua

* If you already have some minimal experience with programming: http://tylerneylon.com/a/learn-lua/
* If you're completely new to programming general: https://youtu.be/iMacxZQMPXs

### Lua in Dokkan

Lua scripts for battle animations are not run live. The scripts are not executing while the animation is playing. The scripts are run before the animation plays to build a queue of instructions that the game code will execute.

Most of the scripts are...poorly maintained.

**Variable Definitions:**
```lua
-- The values of variables like the ones below are references to sound effects
-- They link to sound_effect_offsets.sound_effect_id
SE_01 = 1035;
SE_02 = 1036;
SE_XX = XXXX;

-- The values of the variables below are references LWF files
-- They link to effect_packs.id
SP_01 = 100230;
SP_02 = 100231;
SP_XX = XXXXXX;

-- These are not hard rules. Variables can be named anything, you don't have to follow the SE_XX nomenclature they established. (and they break this themselves)
```

**Dokkan provides the following special functions that scripts can call:**
```lua
-- I will provide parameters for all of these functions in the future
changeAnime()
dealDamage()
delayAll()
delayChara()
endPhase()
entryEffect(startCount, effectPackId, attributes, targetAssignMode, target, startOffsetPosX, startOffsetPosY, isPausable)
entryEffectAwaken()
entryEffectLife(startCount, effectPackId, life, attributes, targetAssignMode, target, startOffsetPosX, startOffsetPosY, isPausable)
entryEffectTraining()
entryEffectUnpausable(startCount, effectPackId, attributes, targetAssignMode, target, startOffsetPosX, startOffsetPosY)
entryFade()
entryFadeBg()
entryFlash()
entryFlashBg()
entryKakimoji()
gotoPhase()
hideCountdownLabel()
hideMessageLabel()
pauseAll()
pauseChara()
playSe()
playSeLife()
playVoice()
recover()
removeAllEffect()
removeAllFade()
removeAllFadeBg()
setAnimeLoop()
setBgGaussBlurKey()
setBgScroll()
setDamage()
setDisp()
setDrawFront()
setEffAlphaKey()
setEffColorKey()
setEffMoveKey()
setEffReplaceTexture()
setEffRotateKey()
setEffScaleKey()
setEffShake()
setEnableAutoXFlip()
setEnvZoomEnable()
setGaussBlurKey()
setLastPosKey()
setMoveKey()
setPhase()
setQuake()
setRotateKey()
setScaleKey()
setSeVolume()
setShake()
setShakeChara()
setVisibleUI()
setVoiceVolume()
setZanzou()
setZanzouColor()
setZanzouSpeed()
showCountdownLabel()
showMessageLabel()
startBgScroll()
stopBgScroll()
stopSe()
stopSeQueueId()
stopVoice()
```

**Dokkan provides the following global variables that scripts can access:**
```lua
_IS_DEAD_
_IS_DEAD_LAST_
_IS_PLAYER_SIDE_
_IS_EXTRA_ATTACK_
_IS_KI_100_
_IS_DOKKAN_MODE_
_IS_SPECIAL_ATTACK_
_IS_SPECIAL_AIM_ALL_
_IS_GUARD_
_IS_ZAWAKEN_
_IS_ATK_FLASH_MOVE_END_
_IS_DFC_FLASH_MOVE_END_
_IS_FINISH_SPECIAL_ONLY_
_IS_DODGE_
_IS_CRITICAL_
_SPECIAL_ENERGY_COLOR_
_SPECIAL_SKILL_LEVEL_
```

