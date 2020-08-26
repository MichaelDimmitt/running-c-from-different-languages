
# Elixir
nif in elixir with no fault tolerance<br/>

bash command to run if erlang was installed with homebrew<br/>
```bash
cc -fPIC -I /usr/local/lib/erlang/erts-11.0.3/include/
	-dynamiclib -undefined dynamic_lookup      
	-o fast_compare.so fast_compare.c
```

to run the program simply execute 
```bash
cd elixir;
elixir runner.exs 
```


https://andrealeopardi.com/posts/using-c-from-elixir-with-nifs/<br/>
code link1:<br/>
code link2: https://github.com/SweetIQ/expostal


# Javascript / Node
Not exactly c, running C++ program with drivers from node to v8 engine.<br/>
https://nodejs.org/api/addons.html<br/>
code link: 

Able to run c programs but not related to v8 engine.<br/>
https://nodejs.org/api/n-api.html<br/>
code link: 

Unsecure alternative - Child Process<br/>
code link1:<br/>
code link2: https://github.com/md-vanilla/simp-js_term<br/>

#Rust
writing NIF's in rust<br/>
https://github.com/rusterlium/rustler<br/>

#Go
link: https://karthikkaranth.me/blog/calling-c-code-from-go/
