* �ꎠ��莺������������妤

* ���掽��Ĳ꤃
** x64 Windows + Visual Studio
** Linux + gcc, clang

* ���掽��̻쵕

** ���夣�⎤�㎫������������倂
```
md work
git clone git@github.com:herumi/xbyak.git
git clone git@github.com:herumi/cybozulib.git
git clone git@github.com:herumi/mcl.git
git clone git@github.com:herumi/sum_crypto.git
git clone git@github.com:herumi/cybozulib_ext.git # only for Windows
```
** `sum_crypto.cpp'���夵�㎳���夦�㎫��������
Windows�Ꭺ��
```
cd sum_crypto
mk.bat
```
Linux�Ꭺ��
```
make
```

** 躀꼎��Ꭰ���鎧�环�뺷�Ꭸ�厬���뺷���掽�����������
```
./sum_crypto.exe init
```
** �⎵�㎼�����𷎷�������倂
```
cd sum_crypto
python server.py
```

** ��
Firefox, Chrome�Ꭾ�Ꭹ�Ꭱ�����Ꭷ
`index.html`
��������倂
