
set(SOURCES
	imconfig.h
	imgui.h
	imgui.cpp
	imgui_draw.cpp
	imgui_internal.h
	imgui_widgets.cpp
	imstb_rectpack.h
	imstb_textedit.h
	imstb_truetype.h
	imgui_demo.cpp
	imgui_tables.cpp
)

add_library(imgui STATIC ${SOURCES})