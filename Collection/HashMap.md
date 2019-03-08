
# hash()方法
~~~
    static final int hash(Object key) {
        int h;
        // key的hash值取最高位做异或运算
        return (key == null) ? 0 : (h = key.hashCode()) ^ (h >>> 16);
    }
~~~
