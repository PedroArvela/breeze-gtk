install(DIRECTORY gtk-2.0 DESTINATION ${KDE_INSTALL_FULL_DATAROOTDIR}/themes/Breeze
    ${directory_EXCLUDES})
install(DIRECTORY assets DESTINATION ${KDE_INSTALL_FULL_DATAROOTDIR}/themes/Breeze
        ${directory_EXCLUDES})

install(DIRECTORY gtk-3.0 DESTINATION ${KDE_INSTALL_FULL_DATAROOTDIR}/themes/Breeze)
install(DIRECTORY gtk-3.18 DESTINATION ${KDE_INSTALL_FULL_DATAROOTDIR}/themes/Breeze)
install(DIRECTORY gtk-3.20 DESTINATION ${KDE_INSTALL_FULL_DATAROOTDIR}/themes/Breeze)
