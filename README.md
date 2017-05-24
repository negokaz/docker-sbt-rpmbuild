# sbt rpmbuild

## Usage

Run following a command in your sbt project root.

```bash
docker run -rm -v .:/project -v ~/.ivy2:/root/.ivy2 negokaz/sbt-rpmbuild rpm:packageBin
```
