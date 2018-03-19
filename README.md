# sha2
Fast software implementation in C of the FIPS 180-2 hash algorithms SHA-224, SHA-256, SHA-384 and SHA-512

## 计算数据的校验和
  - 数据类型: 文件, 字符串
  - 校验和类型: SHA-224, SHA-256, SHA-384 and SHA-512

## 以SHA-512为例:
  - sha512(message, len, digest): 计算字符串的校验和
  - sha512_file(file_name, digest): 计算文件的校验和
