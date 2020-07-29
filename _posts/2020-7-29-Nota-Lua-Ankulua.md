---
layout:  post
title:  Nota Lua Ankulua
---

#### Nota untuk `if` dan `while do`
````lua
--Never ending loop
while do
--Statement
end
````
Contoh `if`
````lua
--Hanya running sekali sahaja
if --this thing true-- then
--do this--
end
````
Contoh `while` + `if` dan `elseif`,
````lua
while (true) do --Loop start
 --Function start
  if find("1.png") then
  --do something
  elseif exists("2.png") then
  --do something
  elseif exists("3.png") then
  --do something
  elseif exists("4.png") then
  --do something
  end --function end
end --Loop end and will return to initial start
````
Loop akan berjalan selama mana statement `true`,selitkan `break` untuk menamatkan loop.
