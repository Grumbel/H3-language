env = Environment()
env.ParseConfig("sdl-config --libs --cflags")
env.Append(LIBS = ["SDL_image","SDL_gfx","libnoise"] )
env.Append(CXXFLAGS =[ "-std=c++0x",
                       "-Wall",
                       "-ansi",
                       "-pedantic" ])
env.Program("h3", Glob("./src/*.cpp"))

# EOF #
