# mapnik-msvc

[Mapnik](https://github.com/mapnik/mapnik) projects for Microsoft Visual Studio 2010.

If you want to build and test mapnik quickly on windows with msvc2010, please checkout and try.

The projects are depend on [mapnik-deps](https://github.com/avlee/mapnik-deps.git)

Supported mapnik versions: `2.3.x`

Usage:

    mkdir mapnik-dev
    
    cd mapnik-dev
    
    git clone https://github.com/mapnik/mapnik.git
    
    git clone https://github.com/avlee/mapnik-deps.git
    
    cd mapnik-deps
    
    unpack
    
    cd ..
    
    cd mapnik
    
    git checkout 2.3.x
    
    git clone https://github.com/avlee/mapnik-msvc.git
    
    cd mapnik-msvc
    
    vcbuild