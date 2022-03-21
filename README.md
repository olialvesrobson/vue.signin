# The simplest Vue SignIn

> This is Sign-in page with Tailwind CSS.


```sh
<template>
    <div class="p-6 max-w-sm mx-auto bg-indigo-900 rounded-xl shadow-md mt-2 flex items-center space-x-4">
        <form action="" method="submit">
            <div class="relative w-100 h-40 overflow-hidden mb-8">
                <img src="https://img.freepik.com/free-vector/abstract-background-consisting-colorful-arcs-illustration_456031-149.jpg?t=st=1647772609~exp=1647773209~hmac=c782f2b170826554a2861d402a89e135ea094d72505e8ecc42017bb69c2cee69&w=2000" 
                    alt="Avatar" class="max-w rounded-xl mb-5 object-cover" />
                <div class="absolute w-full py-3 bottom-10 inset-x-0 bg-transparent text-white text-xl text-center hover:translate-y-1 delay-500">Sign In</div>
            </div>

            <div class="grid ">
                <div class="grid mb-5">
                    <label for="uname"><b>Username</b></label>
                    <input type="text" 
                        placeholder="Enter Username" 
                        name="uname"
                        required
                        class="rounded p-1.5 border border-x border-slate-600 ">
                </div>

                <div class="grid mb-5">
                    <label for="psw"><b>Password</b></label>
                    <input type="password" 
                        placeholder="Enter Password" 
                        name="psw" 
                        required
                        class="rounded p-1.5 border border-gray">
                </div>

                <button class="text-neutral-200 bg-teal-600 space-x-4 my-5 w-36 justify-self-center py-1 rounded">
                    Sign in
                </button>
                
                <label>
                <input type="checkbox" checked="checked" name="remember"> Remember me
                </label>
            </div>

            <div class="grid space-x-4"  >
                <button type="button" class="bg-gray-600 text-neutral-200 space-x-4 mx-3 my-5 rounded cancelbtn">Cancel</button>
                <span class="psw text-emerald-200">Forgot <a href="#">password?</a></span>
            </div>
        </form>
    </div>

    
</template>
```