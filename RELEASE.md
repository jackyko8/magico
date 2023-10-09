# Release Notes

Verion 1.0 2023-10-09
- Added documentation: Sphinx and readthedocs
- Fix .readthedocs.yaml with docs/source/conf.py

Version 0.3.5 2023-10-09
- Export __name__, __version__, and __description__

Version 0.3.4 2023-09-24
- Add data_type()
- Fix __iter__ so it returns MagicO for list and tuple
- Add inline documentation

Version 0.3.3 2023-09-20
- Fix list and tuple containment check

Version 0.3.2 2023-09-20
- Exclude overriding methods from _type_method_list

Version 0.3.1 2023-09-20
- Typos

Version 0.3 2023-09-20
- Add tuple
  - No benefit using MagicO on a set as its items need to be hashable

Version 0.2 2023-09-19
- Auto-discover type methods `get_callable_names()`
- Add magico_types = Union[dict, list]
- Refind tutorial and README.md

Version 0.1 2023-09-18
- First release
