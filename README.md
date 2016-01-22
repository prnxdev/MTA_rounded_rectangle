### Create rounded rectangles with this function!
Easy to use, cool effect. Why not to use?
1 thing - enable OOP in meta.xml

```
<meta>
  ...
  <oop>true</oop>
  ...
</meta>
```

##### SIMPLE AF
```
local texture = dxCreateRoundedRectangle(300,40,50) -- width: 300px, height: 40px, radius: 50% (0-100%)

addEventHandler("onClientRender",root,
  function()
    if texture then
      dxDrawImage(0,0,300,40,texture) -- drawing rounded texture at [0,0] with size [300,40]
    end
  end
end)
```

#### TODO
Add antyaliasing. Meybe to add more performance (not tested, just wrote and pulled). 
If you know how to make code better - DO IT! YES, YOU CAN! YESTERDAY YOU SAID TOMORROW!

cheers.
