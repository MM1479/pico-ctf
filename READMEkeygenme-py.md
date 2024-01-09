# keygenme-py
The following part of the given code stands out

<img width="583" alt="image" src="https://github.com/MM1479/picoCTF/assets/148882111/3bd5b4a1-f8b4-4ab7-9829-29a46ab13375">

The key is made of 3 parts, first and third of which are clearly given.
The second is the dynamic part which we have to figure out.

![image](https://github.com/MM1479/pico-ctf/assets/148882111/c7a7d3bc-9a14-47e1-879a-818e6639c777)
![image](https://github.com/MM1479/pico-ctf/assets/148882111/774cd600-3439-4bdd-b103-b72ad84932f1)

The above part of the code seems to check whether the activation key given is correct or not.
It uses a fuction hashlib which seems to be for hashing.

Opening webshell and using wget command to download the python file onto the shell.

<img width="913" alt="image" src="https://github.com/MM1479/pico-ctf/assets/148882111/f999274c-8c2b-4cf5-a914-e440f201afa7">

On python, imported the hashlib module and used the command given in the code: hashlib.sha256(b"FREEMAN").hexdigest()
which converts the hash object into a hexadecimal string

Note: SHA-256 is a widely used cryptographic algorithm that produces a fixed-length, 256-bit (32-byte) hash value

<img width="428" alt="image" src="https://github.com/MM1479/pico-ctf/assets/148882111/b7c07853-655a-4ad5-8090-30e0c0785023">

Copied the same values into the dynamic part of the key.

Key: picoCTF{1n_7h3_|<3y_of_0d208392}
