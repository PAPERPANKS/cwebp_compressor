# cwebp_compressor

Well first of all you have to download the cwebp compressor tool according to your machine(Windows|Linux) from [here][1].

Now after extracting the folder in `C:\Program Files\` you have to [set path][2] to `cwebp.exe`, below is my path
`Path:: C:\Program Files\libwebp\bin`

Open cmd to check if you have done right till now.

 - `cmd> cwebp -version`

[![cwebp- version][3]][3]

 - `cmd> python --version` 

[![python --version][4]][4]

Now it's super easy just run the below command and you have your desired output.

`cmd> python cwebp_compressor.py folder-name quality ` 

`quality can be between [0-100]`
   
  [1]: https://developers.google.com/speed/webp/download
  [2]: https://www.computerhope.com/issues/ch000549.htm
  [3]: https://i.stack.imgur.com/YoL6I.png
  [4]: https://i.stack.imgur.com/etcwW.png
