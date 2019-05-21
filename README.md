  ![XSSer](https://xsser.03c8.net/xsser/zika1.png "XSSerBanner")

=================================================================== 

 Cross Site "Scripter" (aka XSSer) is an automatic -framework- to detect, exploit and report XSS vulnerabilities.

----------
    
    git clone https://github.com/4k4xs4pH1r3/xsser.git && cd xsser
    
#

    xsser -d http://192.70.197.235:9000/ --De bing -c 50 --Cw 5 --Cl -s -v --hash --heuristic --user-agent Googlebot/2.1 (+http://www.google.com/bot.html) --reverse-check --threads 5 --timeout 30 --retries 1 --delay 0 --auto --Str --Une --Hex --Hes --Dwo --Doo --Dec --Coo --Xsa --Xsr --Dom --Dcp --Ind --Anchor --Phpids0.6.5 --Phpids0.7 --Imperva --Webknight --F5bigip --Barracuda --Modsec --Quickdefense --Onm --Ifr --save --xml xsser-test:2019-05-21 17:53:53.034471.xml


 XSSer is released under the GPLv3. You can find the full license text
in the [COPYING](./xsser/doc/COPYING) file.

----------

 + Web:  https://xsser.03c8.net

----------

  ![XSSer](https://xsser.03c8.net/xsser/zika2.png "XSSerManifesto")

#### Installing:

 XSSer runs on many platforms. It requires Python and the following libraries:

    - python-pycurl - Python bindings to libcurl
    - python-xmlbuilder - create xml/(x)html files - Python 2.x
    - python-beautifulsoup - error-tolerant HTML parser for Python
    - python-geoip - Python bindings for the GeoIP IP-to-country resolver library

 On Debian-based systems (ex: Ubuntu), run: 

    sudo apt-get install python-pycurl python-xmlbuilder python-beautifulsoup python-geoip

 On other systems such as: Kali, Ubuntu, ArchLinux, ParrotSec, Fedora, etc... also run:

       pip install geoip 

####  Source libs:

       * Python: https://www.python.org/downloads/
       * PyCurl: http://pycurl.sourceforge.net/
       * PyBeautifulSoup: https://pypi.python.org/pypi/BeautifulSoup
       * PyGeoIP: https://pypi.python.org/pypi/GeoIP

----------

####  Screenshots:

  ![XSSer](https://xsser.03c8.net/xsser/url_generation.png "XSSerSchema")

  ![XSSer](https://xsser.03c8.net/xsser/zika3.png "XSSerAdvanced")

  ![XSSer](https://xsser.03c8.net/xsser/zika4.png "XSSerGeoMap")

