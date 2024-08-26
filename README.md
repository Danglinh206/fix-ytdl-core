# fix-ytdl-core
Cách Fix ytdl-core by Thanh Loc

"ytdl-core": "github:ThanhLoc04/ytdl-core#sig-patch" : dòng này thay vào package.json 

vào package-lock.json xoá ytdl-core cũ đi
LƯU Ý! trong package-lock.json 
phần undici theo bản này 
"undici": {
      "version": "5.28.4",
      "resolved": "https://registry.npmjs.org/undici/-/undici-5.28.4.tgz",
      "integrity": "sha512-72RFADWFqKmUb2hmmvNODKL3p9hcB6Gt2DOQMis1SEBaV6a4MH8soBvzg+95CYhCKPFedut2JY9bMfrDl9D23g==",
      "requires": {
        "@fastify/busboy": "^2.0.0"
      }
    },
cứ npm i lại là xong. 
