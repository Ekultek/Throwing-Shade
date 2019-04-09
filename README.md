# Throwing Shade

As many of you are aware, a lot of shade has been being thrown towards my name, kicking dirt on my projects, my contributions and me as well. So we're gonna go ahead and clear the air right now. 

### Git diffs of every single waf detection script in whatwaf against sqlmap

For those of you unfamiliar with `git diff` white is exactly the same `red` is whatwaf `green` is sqlmap. I'm going to leave out the ones that are not implemented in one or the other (for example if sqlmap doesnt have it, I won't include it, if whatwaf doesn't have etc). I have specifically chosen the most similar waf detection scripts for this, let us begin:

 - 360.py

![360GitDiff](https://user-images.githubusercontent.com/14183473/55806763-87bea500-5aa6-11e9-939c-b3121a9b0caa.png)

 - airlock.py
 
![airLockGitDiff](https://user-images.githubusercontent.com/14183473/55806871-c2284200-5aa6-11e9-8d11-959b9f235262.png)

 - anquanbao.py

![aqGitDiff](https://user-images.githubusercontent.com/14183473/55807006-0b789180-5aa7-11e9-940d-a1706c3f25d2.png)

 - armor.py

![armorGitDiff](https://user-images.githubusercontent.com/14183473/55807068-2fd46e00-5aa7-11e9-95cf-e6db64212bc3.png)

 - asm.py

![asmGitDiff](https://user-images.githubusercontent.com/14183473/55807258-80e46200-5aa7-11e9-9728-169e6dfc6af0.png)


I really dont think I need to continue, if I do need to or you want me to add some more to this please let me know or make an issue in this repo asking for it.