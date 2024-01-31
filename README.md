Warning: this is a debug build of cabal-install with assertions enabled.
Warning: Parsing the index cache failed (Data.Binary.Get.runGet at position
16: Non-matching structured hashes: f46da61e7afa58a5e8fd1d2b6fb79899;
expected: d81bdd513f41b5d7ee4cd28455adadbe). Trying to regenerate the index
cache...
Resolving dependencies...
Build profile: -w ghc-9.6.2 -O1
In order, the following will be built (use -v for more details):
 - acme-box-0.0.0.0 (lib) (requires build)
 - p1-0.1.0.0 (lib) (first run)
Starting     acme-box-0.0.0.0 (lib)
Building     acme-box-0.0.0.0 (lib)
Installing   acme-box-0.0.0.0 (lib)
[GlobalPackageDB,SpecificPackageDB "/home/matt/cabal-rodrigo/repro/new_store/ghc-9.6.2/package.db"]
[GlobalPackageDB,SpecificPackageDB "/home/matt/cabal-rodrigo/repro/new_store/ghc-9.6.2/package.db"]
Completed    acme-box-0.0.0.0 (lib)
Warning: this is a debug build of cabal-install with assertions enabled.
Configuring library for p1-0.1.0.0...
Warning: this is a debug build of cabal-install with assertions enabled.
Preprocessing library for p1-0.1.0.0...
Building library for p1-0.1.0.0...
[1 of 1] Compiling MyLib            ( src/MyLib.hs, /home/matt/cabal-rodrigo/repro/dist-newstyle/build/x86_64-linux/ghc-9.6.2/p1-0.1.0.0/build/MyLib.o, /home/matt/cabal-rodrigo/repro/dist-newstyle/build/x86_64-linux/ghc-9.6.2/p1-0.1.0.0/build/MyLib.dyn_o )
Warning: this is a debug build of cabal-install with assertions enabled.
Warning: this is a debug build of cabal-install with assertions enabled.
Resolving dependencies...
Build profile: -w ghc-9.6.2 -O1
In order, the following will be built (use -v for more details):
 - containers-0.7 (lib) (requires build)
 - p2-0.1.0.0 (lib) (first run)
Starting     containers-0.7 (lib)
Building     containers-0.7 (lib)
Installing   containers-0.7 (lib)
[GlobalPackageDB,SpecificPackageDB "/home/matt/cabal-rodrigo/repro/new_new_store/ghc-9.6.2/package.db"]
[GlobalPackageDB,SpecificPackageDB "/home/matt/cabal-rodrigo/repro/new_new_store/ghc-9.6.2/package.db",SpecificPackageDB "/home/matt/cabal-rodrigo/repro/new_store/ghc-9.6.2/package.db/"]
Assertion failed
CallStack (from HasCallStack):
  assert, called at src/Distribution/Client/ProjectBuilding/UnpackedPackage.hs:684:21 in cabal-install-3.11.0.0-inplace:Distribution.Client.ProjectBuilding.UnpackedPackage

