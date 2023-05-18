# fork of [python module for MeCab 0.996](https://bitbucket.org/eunjeon/mecab-python-0.996/)
===================================

## 소개

[konlpy](https://github.com/konlpy/konlpy)에서 제공하는 [MeCab 설치 코드](https://github.com/konlpy/konlpy/blob/master/scripts/mecab.sh) 중 [eunjeon/mecab-python-0.996] 레포지토리를 이용하는 [부분](https://github.com/konlpy/konlpy/blob/master/scripts/mecab.sh#L156)이 특정 환경에서 제대로 작동하지 않는 문제가 있어, 이를 해결하기 위한 workaround 용도로 생성한 소스입니다.

## 설치

    :::text
    % git clone https://github.com/shhommychon/mecab-python-0.996.alt.git
    % cd mecab-python-0.996
    % python setup.py build
    % su
    # python setup.py install
  
You can change the install directory with the --prefix option. For example:

    :::text
    % python setup.py install --prefix=/tmp/pybuild/foobar

## 사용법

샘플 프로그램인 test.py를 참조하세요.

## 라이센스
mecab-ko의 라이센스는 MeCab의 라이센스를 그대로 따릅니다.

> MeCab 는 무료 소프트웨어입니다. GPL (the GNU General Public License), LGPL (Lesser GNU General Public License) 또는 BSD 라이선스에 따라 소프트웨어를 사용, 재배포할 수 있습니다. 자세한 내용은 COPYING, GPL, LGPL, BSD 각 파일을 참조하십시오.
