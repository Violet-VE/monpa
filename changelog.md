**monpa v0.2.5.1**
- force incomplete sentence can be output word and pos without error message. ex.『隔離百分之』can be output as [['隔離', 'VC'], ['百分之', 'Neqa']], although "百分之" is incomplete.
- fix load_userdict function to avoid output dubplicate user define terms.
- fintune some wording. 

monpa v0.2.5
- fine turn LICENSE to BSD
- revision `__init__.py` and README.md
- revise author email at `setup.py`
- release date: 2019/07/26

monpa v0.2.4.1
- add package dependence to check `torch >= 1.0` and `requests`, if false, pip install directly.

monpa v0.2.4
- fix model folder issue

monpa v0.2.3
- due to pypi file size limitation, revision for not include model file in wheel but invoking download when 1st time import.

monpa v.0.2.2
- add `cut`, `pseg`, `load_userdict` function
- fix file path issue
- fix CP950 issue: when open file by setting encoding="utf-8"
- `setup.py` revision
- README.md revision
- release date: 2019/07/23

monpa v0.2.1
- adopt new training model