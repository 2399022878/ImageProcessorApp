ÿ�ο�ʼд��ʱ����ǵÿ������⻷����

```bash
.\env\Scripts\activate
```

git�������м�¼

- ��������github�ϴ����Ĳֿ�

```
git remote add origin https://github.com/2399022878/ImageProcessorApp.git
```

- �ύ���뵽github

```
# ��ʼ�����زֿ⣨�����δ��ʼ����
git init

# ����ļ����ύ
git add .
git commit -m "Initial commit"

# ����Զ�ֿ̲⣨�״Σ�
git remote add origin https://github.com/2399022878/ImageProcessorApp.git

# ���͵�Զ��
git push -u origin main
```

- ����vscode���source controlͼ�꣨ctrl+shift+g��,��ѡ�ļ��������ύ��Ϣ
- ÿ�տ�������

```
git pull origin main  # ��ʼǰ����ȡ���´���
git checkout -b dev-feature1  # Ϊ�¹��ܴ�����֧
# ������ɺ�...
git add .
git commit -m "Add image resize function"
git push origin dev-feature1
# �� GitHub �ύ Pull Request �ϲ��� main
```
