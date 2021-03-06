# registry.nocsi.org/odroidc2-linux  

[`registry.nocsi.org/odroidc2-linux`][1] is a [docker][2] image that bundles the following:  
* **[Linux 3.14.y-android][3]:**

## Details
* The following volumes exist:  
  - /linux
  - /opt/toolchains
* /linux is your default workdir. *Knowing this will be helpful when you're mounting your playbooks for execution.*   

## Usage 
This image can easily be extended.  

````
docker run --rm=true 
        -v $(pwd)/out:/linxu/src \
	registry.nocsi.org/odroidc2-linux:3.14.y-android 
````

## Misc. Info 
* Latest version: 3.14.y-android   
* Built on: 2017-05-12T21:12:58EDT   
* Base image: registry.nocsi.org/archlinux-aur:latest ([dockerfile][6])  
* [Dockerfile][7]

[1]: https://hub.docker.com/r/registry.nocsi.org/odroidc2-linux/   
[2]: https://docker.com 
