documentation here http://opam.ocamlpro.com/
Installation
----------------
- install it manualy:
git clone git://github.com/OCamlPro/opam.git
cd opam
git checkout 0.7.7
./configure
make
make install
- with brew
brew update
brew install opam
- configure it:
opam init
eval `opam config -env`
echo "eval \`opam config -env\`" >> ~/.bashrc

Setup
----------------
        # opam remote -add default2 git://github.com/hhugo/opam-repository.git 50
          opam remote -add besport git://github.com/besport/opam-repo-besport.git 100
          opam update
          opam install ocamlfind deriving-ocsigen js_of_ocaml eliom tyxml ocsigenserver camlzip sqlite3-ocaml aws pcre-ocaml leveldb yojson xmlm aliases imagemagick sqlite3-ocaml csv


Other dependencies
----------------
- google-perftools (1.7 for osx)
- libsnappy
