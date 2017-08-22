# gpio_lib_c
  GPIO_LIB is a extension of Wiring, it can control low speed peripherial of Tinker Board.
  
# getting source code
  1. make sure network is work fine.
  2. sudo apt-get update
     sudo apt-get install git
  3. git clone https://github.com/org-testing/gpio_lib_c.git

# how to build
  cd gpio_lib_c\
  chmod a+x build\
  sudo ./build

  It will build specific project you define in build. the default folder are gpio, example,...
  if you create new c file, you need to modify Makefile to compile it.

  If you want to build it by gcc directly, you need to add flag -DASUS_TINKER.
  
# usage
  cd gpio\
  gpio readall

# troubleshooting
  If you meet ssl issue as below "fatal: unable to access 'https://github.com/org-testing/gpio_lib_c.git/': server certificate verification failed. CAfile: /etc/ssl/certs/ca-certificates.crt CRLfile: none"
  
  short-term solution is export GIT_SSL_NO_VERIFY=1.
# more information
  You can refer to URL.
