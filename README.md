```
# clone fullstack repository
git clone --recurse-submodules https://github.com/lore-land/lorebone.git;

# enter fullstack directory
cd lorebone;

# initialize frontend
cd boon;
yarn install;
yarn build;

# re-enter lorebone root
cd ..;

# serve application
cargo run --manifest-path bone/Cargo.toml;

# visit this url in your browser:
#   https://localhost:8080
```
