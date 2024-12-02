# key_pair_generate

## 1. Generating SSH key-pairs(public key, private key) using ssh keygen

### 1.1 Generate the public key and private key

Before you start playing with AWS console and terraform script we need to first generate the key-pair(public key, private key) using ssh-keygen.
Later we are going to associate both public and private keys with AWS EC2 instances.
Let us generate the key pair using the following command

```hcl
 ssh-keygen -t rsa -b 2048 
```

<br>

By default, the above command will generate the public as well as private key at location '/c/Users/JETTI.RAMA SAI/.ssh/id_rsa'
But we can override the end destination with a custom path.

D:\terraform key_pair

```hcl
 D:\terraform key_pair\<key_pair_name>
```

<br>

Enter passphrase (empty for no passphrase): ***Please click on the enter button***

Enter same passphrase again: ***Again please click on the enter button***
![Screenshot (124)](https://github.com/user-attachments/assets/e26a7523-a148-4c81-ab9f-868cc52e9b15)

<br>





