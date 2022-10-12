# Mining-Unit-Status

(1) Install this LUA code on a Programming Board by:
  - press CTRL+L to open LUA (while reticle is pointing at the programming board)
  - select the default "unit" slot then ADD FILTER "onStart()"
  - Now copy and paste the LUA code from the text file
  - Click APPLY to save

(2) Link Programming Board to a Screen (any size) using link tool (Build mode)
  - press CTRL+L to open LUA (while reticle is pointing at the programming board)
  - rename the new slot from "slot1" to "screen"
  - Click APPLY to save
  
(3) Link Programming Board to a Mining Unit using the link tool (Build mode)
  - press CTRL+L to open LUA (while reticle is pointing at the programming board)
  - rename the new slot from "slot2" to "MU"
  - Click APPLY to save
  
(4) Optional - Link Programming Board to a Light using the link tool (Build mode)
    - press CTRL+L to open LUA (while reticle is pointing at the programming board)
    - then rename the new slot from "slot3" to "light"
    - Click APPLY to save
    
(5) Activate your Programming Board

Optionally - you can add a Detection Zone element and link it to the Programming Board to automatically activate it when detection zone triggers

You can modify the LUA Parameters to meet your needs:
  - GreenThreshold - default = 75
  - YellowThreshold - default = 50
  - lightIndicator - default = "Y"
  - backgroundImage default = "assets.prod.novaquark.com/16944/f1c2e89d-bcdb-44bf-ab5b-fb1f770d8f2c.jpg"
