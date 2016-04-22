# 20160422
練習中♪
ははは

```ruby
puts 'The best way to log and share programmers knowledge.'
```
```c
int main()
```
```c
int i2c_receive(unsigned char adrs,int len,unsigned char *buf)
{
    int i = 0;
    Wire.requestFrom((int)adrs,len);
    while(Wire.available()){
        buf[i] = Wire.read();
        i++;
    }
}
```c
