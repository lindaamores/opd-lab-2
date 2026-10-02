Джуниор  
**Сцена** PlatformerDemo:  
представляет собой уровень с прыжками. Имеется:  
	– Tree Background \- лес  
	– Character \- персонаж  
	– Grass \- трава  
	– Levers \- рычаги  
**Player**:  
   Inspector:  
	– Rigidbody 2D  
	– Animator  
	– Capsule Collider 2D  
	– Skript  
   Hand (в Hierarchy)  
**Скрипты**:  
– CarryItem \- нести предмет. Персонаж может носить ключ  
– Character \- персонаж, его физика, анимации  
– CharacterHoldlte \- ссылки на Animator, Rigidbody 2D и др  
– FollowCamera \- камера следует за персонажем  
– levers \- рычаги, взаимодействие с ними  
– ParallaxBackground \- лес следует за персонажем как фон  
– PlayerCharacter \- управление персонажем: прыжки, приседание и тд  
– PlayerControls \- управление персонажем: кнопки  
– TheAudio \- саундтрек игры.