ADD_SUBDIRECTORY(g2o_cli)
ADD_SUBDIRECTORY(g2o_simulator)

IF(QT4_FOUND AND QGLVIEWER_FOUND)
  ADD_SUBDIRECTORY(g2o_viewer)
ENDIF(QT4_FOUND AND QGLVIEWER_FOUND)
