ÿ�ο�ʼд��ʱ����ǵÿ������⻷����

```bash
.\env\Scripts\activate
```

git�������м�¼

- ��������github�ϴ����Ĳֿ�

```
git remote add origin https://github.com/Linda/ImageProcessorApp.git
```

- �ύ���뵽github

```
git add .  # ��������ļ����ݴ���
git commit -m "Initial commit: setup project environment"  # �ύ�����زֿ�
git branch -M main  # ������Ĭ�Ϸ�֧Ϊ main����ѡ��
git push -u origin main  # ���͵� GitHub
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
