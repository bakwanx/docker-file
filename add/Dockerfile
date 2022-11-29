
FROM alpine:3

# perintah RUN hanya dijalankan ketika build saja
RUN mkdir hello

# command dibawah digunakan utk memindahkan file world.txt ke folder hello
ADD text/world.txt hello
# bisa aja pakai perintah yang mudah dgn menggunakan
# match pattern milik Golang sehingga tidak perlu add satu2
# seperti ini dengan specific :
# ADD text/*.txt hello
# atau mau add semua file : 
# ADD text/* hello

CMD cat "hello/world.txt"