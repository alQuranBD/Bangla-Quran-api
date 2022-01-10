# Bangla-Quran-api

This is an REST API of Holy Quran with translation in Bangla and English.
This api also includes the tafseer Tafhimul Quran

<p align="left"> <img src="https://komarev.com/ghpvc/?username=alQuranBD&label=Views&color=0e75b6&style=flat" alt="niamulhasan" /> </p>


# The API at a glance

 **ROOT URI : ``http://alquranbd.com/api/``**


| URI                                                  | Parameters                                                                 | Response                                       | Example Call                                                         |
|------------------------------------------------------|----------------------------------------------------------------------------|------------------------------------------------|----------------------------------------------------------------------|
| ROOT/tafheem/sura/list                               | none                                                                       | JSON List of the Hadith books                  | <sub><sup>https://alquranbd.com/api/tafheem/sura/list<sub><sup>      |
| ROOT/tafheem/suraData/`:sura_no`/`:page_no`          | `sura_no` : int; `page_no : int                                            | JSON List of ayas                              | <sub><sup>https://alquranbd.com/api/tafheem/suraData/2/3<sub><sup>   |
