# gpio_lib_c
  GPIO_LIB is a extension of Wiring, it can control low speed peripherial of Tinker Board.
  
# getting source code
  type the command on shell of Tinker Board\
  git clone https://github.com/org-testing/gpio_lib_c.git

# how to build
  cd gpio_lib_c\
  chmod a+x build\
  ./build

  It will build specific project you define in build. the default folder are gpio, example,...
  if you create new c file, you need to modify Makefile to compile it.

  If you want to build it by gcc directly, you need to add flag -DASUS_TINKER.
