INCLUDE_DIRECTORIES( ${TIFF_INCLUDE_DIR} )

SET(TARGET_SRC ReaderWriterTIFF.cpp )

SET(TARGET_LIBRARIES_VARS TIFF_LIBRARY JPEG_LIBRARY LIBLZMA_LIBRARY)

#### end var setup  ###
SETUP_PLUGIN(tiff)
