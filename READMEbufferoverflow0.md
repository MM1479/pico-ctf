# buffer overflow 0
This part of the code contains a command called gets, which is not safe.

<img width="166" alt="image" src="https://github.com/MM1479/pico-ctf/assets/148882111/76082384-f05f-488e-b012-28dc303026ae">

According to the image below, the buffer overflow has to be performed related to this gets command.

<img width="930" alt="image" src="https://github.com/MM1479/pico-ctf/assets/148882111/6db7e08c-2504-47bd-bfd6-465d875585b4">

The vuln function has a maximum size of 16, so let's try putting a size of more than 16.

<img width="178" alt="image" src="https://github.com/MM1479/pico-ctf/assets/148882111/3366566f-605e-4d1f-9888-606a90c87bd1">

Doing so results in the flag below

<img width="680" alt="image" src="https://github.com/MM1479/pico-ctf/assets/148882111/023fa5dc-703d-498d-bb5c-02f93869c1b0">

Flag: picoCTF{ov3rfl0ws_ar3nt_that_bad_9f2364bc}
