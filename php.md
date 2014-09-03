# PHP

cd /usr/local
sudo curl -O  http://pear.php.net/go-pear.phar


sudo cp /etc/php.ini.default /etc/php.ini

include_path = "/usr/local/PEAR:/php/includes"

vi .bash_profile
export PATH="/usr/local/mysql/bin:/Users/benjamin/pear/bin:$PATH"

pear version
pear upgrade pear
pear upgrade




enable xcode command line tools

tar -xvf icu4c-4_8_1_1-src.tgz
cd icu/source
./runConfigureICU MacOSX
make
sudo make install


brew install autoconf

sudo pecl install intl

// Add this to the bottom of your php.ini file
extension=intl.so
