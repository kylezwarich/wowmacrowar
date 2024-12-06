# DUAL WIELD WITH DEPENDENCY
Do a dual wield using MultiBarLeftButton10 and MultiBarLeftButton11 as Main Hand and Off-Hand, respectively
```
#show Dual Wield
/click MultiBarLeftButton10
/click MultiBarLeftButton11
```

# EQUIP SHIELD WITH DEPENDENCY
Do a sword-and-board using MultiBarLeftButton10 and MultiBarLeftButton12 as Main Hand and Shield, respectively
```
#show Defensive Stance
/click MultiBarLeftButton10
/click MultiBarLeftButton12
```

# Shield Bash without a shield equipped with dependency
Do a shield bash in defensive stance or battle stance using MultiBarLeftButton10 and MultiBarLeftButton12 as Main Hand and Shield, respectively
```
#showtooltip Shield Bash
/cast [stance:3] Defensive Stance
/use [@mouseover, exists,Stance:1/2] Shield Bash ; Shield Bash
/stopmacro [equipped: Shields]
/click MultiBarLeftButton10
/click MultiBarLeftButton12
```
