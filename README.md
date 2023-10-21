
# acunetix install in kali linux 

Acunetix is an end-to-end web security scanner that offers a 360 view of an organization's security.


## acunetix Downloads Now:

```bash
  https://drive.google.com/drive/folders/11dmQR4xk0cgvXcTOThK0qPCLwsIdOtIm?usp=sharing
```

1. open the downloads directory

```bash
cd Downloads
```

2. open the Acunetix_13 directory then
```bash
cd Acunetix_13
```

3. Need to file permutation

```bash
chmod +x *
```
4. Run command in terminal

```bash
sudo bash ./acunetix_13.0.200217097_x64_.sh
```
5. Run command in terminal

```bash
sudo cp wvsc /home/acunetix/.acunetix/v_200217097/scanner/
```
6. Run command in terminal

```bash
sudo cp license_info.json /home/acunetix/.acunetix/data/license/
```
7. acunetix status check

```bash
service acunetix status 
```
8. acunetix service run

```bash
service acunetix start
```
9. open the urls in the browser

```bash
https://127.0.0.1:3443/
```
10. acunetix stop

```bash
service acunetix stop 
```

