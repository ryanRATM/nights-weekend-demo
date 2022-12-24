# nights-weekend-demo
sample site to upload data

# TODO
a [tensorflow] convert to tensorflow.js model
b [tensorflow] to run image against model
c [tensorflow] to process image to correct size
d [frontend] display model output on screen
e [backend | aws - lambda] make url signer to generate sign upload url
f [backend | aws - lambda] make endpoint to log image url with label as entry
g [frontend] send response to s3 bucket (keep filename as upload, but store in bucket folder of label)

## PRIORITY
a
c
b
d
e* see if can make it one endpoint, since signed url makes the key
f*
g

## USER EXPERIENCE
1) upload image & provide label
2.a) click submit to create signed url request to upload to s3 and endpoint to log
2.b) run against tensorflow model
3) display output