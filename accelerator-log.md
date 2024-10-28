# Accelerator Log

## Options
```json
{
  "deploymentType" : "tpfork8s",
  "includeBuildToolWrapper" : true,
  "javaVersion" : "21",
  "persistenceType" : "jpa",
  "projectName" : "tanzu-music"
}
```
## Log
```
┏ engine (Chain)
┃  Info Running Chain(Exclude, GeneratorValidationTransform, UniquePath)
┃ ┏ engine.transformations[0] (Exclude)
┃ ┃  Info Will exclude [accelerator.yaml, accelerator.axl]
┃ ┃ Debug accelerator.axl matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug LICENSE didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/test/com/example/music/ApplicationTests.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/albums.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/index.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/css/app.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/css/multi-columns-row.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/js/info.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/js/errors.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/js/status.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/js/albums.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/js/app.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/img/glyphicons-halflings.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/img/glyphicons-halflings-white.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/status.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/list.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/grid.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/albums.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/errors.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/footer.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/header.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/static/templates/albumForm.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/application.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/config/data/RedisConfig.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/web/InfoController.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/web/AlbumController.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/web/ErrorController.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/repositories/AlbumRepositoryPopulator.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/repositories/redis/RedisAlbumRepository.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/repositories/jpa/JpaAlbumRepository.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/repositories/mongodb/MongoAlbumRepository.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/Application.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/domain/ApplicationInfo.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/domain/Album.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug bin/main/com/example/music/domain/RandomIdGenerator.class didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/cloudfoundry/manifest.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/cloudfoundry/project.toml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/kubernetes/deployment.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/kubernetes/service.yaml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/tanzu.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug deploy/tpfork8s/.tanzu/config/spring-music.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug accelerator.yaml matched [accelerator.yaml, accelerator.axl] -> excluded
┃ ┃ Debug README.md didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug build.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gitattributes didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/executionHistory/executionHistory.lock didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/gc.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/fileChanges/last-build.bin didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/dependencies-accessors/gc.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/checksums/checksums.lock didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/checksums/sha1-checksums.bin didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.9/fileHashes/fileHashes.lock didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/gc.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/fileChanges/last-build.bin didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/dependencies-accessors/gc.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/checksums/checksums.lock didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/checksums/md5-checksums.bin didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/checksums/sha1-checksums.bin didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.lock didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.bin didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug gradle.properties didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .vscode/settings.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug settings.gradle didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/gradle.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/.gitignore didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/workspace.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug .idea/misc.xml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/albums.json didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/index.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/css/app.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/info.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/errors.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/status.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/albums.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/js/app.js didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/status.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/list.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/grid.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/albums.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/errors.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/footer.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/header.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/static/templates/albumForm.html didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/resources/application.yml didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/Application.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/config/data/RedisConfig.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/redis/RedisAlbumRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/domain/Album.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┗ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java didn't match [accelerator.yaml, accelerator.axl] -> included
┃ ┏ ┏ engine.transformations[1].validated (Chain)
┃ ┃ ┃  Info Running Chain(ApplyTo, IfElse, IfElse, IfElse, IfElse, ApplyTo, ApplyTo, Let)
┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[0].apply (TextPreprocessor)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1] (IfElse)
┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise (Chain)
┃ ┃ ┃ ┃  Info Running Chain(IfElse, UniquePath)
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0] (IfElse)
┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, ApplyTo)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[0].apply (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceSnippet, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ╺  Info Will replace [spring-music->tanzu-music]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[0].apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┃ ┗ ┗ Debug Path 'deploy/tpfork8s/tanzu.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/, filename=tanzu.yml, g0=deploy/tpfork8s/tanzu.yml, g1=deploy/tpfork8s/, g2=tanzu.yml, g3=tanzu.yml, g4=.yml} and was rewritten to 'tanzu.yml'
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[1].apply (Chain)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ReplaceText, RewritePath)
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[1].apply.transformations[0] (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace [spring-music->tanzu-music]
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[1].otherwise.transformations[0].then.transformations[1].apply.transformations[1] (RewritePath)
┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug Path 'deploy/tpfork8s/.tanzu/config/spring-music.yml' matched '^(?<folder>.*/)?(?<filename>([^/]+?|)(?=(?<ext>\.[^/.]*)?)$)' with groups {ext=.yml, folder=deploy/tpfork8s/.tanzu/config/, filename=spring-music.yml, g0=deploy/tpfork8s/.tanzu/config/spring-music.yml, g1=deploy/tpfork8s/.tanzu/config/, g2=spring-music.yml, g3=spring-music.yml, g4=.yml} and was rewritten to '.tanzu/config/tanzu-music.yml'
┃ ┃ ┃ ┗ ╺ engine.transformations[1].validated.transformations[1].otherwise.transformations[1] (UniquePath)
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[2] (IfElse)
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/mongodb/MongoAlbumRepository.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gitattributes matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .idea/misc.xml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/js/app.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/errors.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/status.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/Album.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/mongodb/MongoAlbumRepository.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug .gradle/8.9/fileHashes/fileHashes.lock matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/ApplicationInfo.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/albums.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/Application.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/grid.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/ErrorController.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.9/dependencies-accessors/gc.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/dependencies-accessors/gc.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.9/fileChanges/last-build.bin matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug gradle.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/RandomIdGenerator.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.bin matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug tanzu.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings.png matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.9/gc.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/footer.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.lock matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/jpa/JpaAlbumRepository.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/config/data/RedisConfig.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/test/com/example/music/ApplicationTests.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug LICENSE matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/fileChanges/last-build.bin matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/InfoController.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .tanzu/config/tanzu-music.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .idea/.gitignore matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug README.md matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/AlbumRepositoryPopulator.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/redis/RedisAlbumRepository.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/css/app.css matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/config/data/RedisConfig.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings-white.png matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/js/status.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/js/errors.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/js/info.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gitignore matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/sha1-checksums.bin matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/application.yml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/sha1-checksums.bin matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/list.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/redis/RedisAlbumRepository.java didn't match [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> excluded
┃ ┃ ┃ ┃ Debug bin/main/static/templates/header.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug build.gradle matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/js/albums.js matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/css/multi-columns-row.css matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug settings.gradle matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/gc.properties matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .vscode/settings.json matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/checksums.lock matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/index.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/checksums.lock matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/AlbumController.class matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/static/templates/albumForm.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/md5-checksums.bin matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug bin/main/albums.json matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┃ Debug .gradle/8.9/executionHistory/executionHistory.lock matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┗ Debug src/main/resources/static/css/multi-columns-row.css matched [!'src/main/java/com/example/music/config/data/**' && !'src/main/java/com/example/music/repositories/mongodb/**' && !'src/main/java/com/example/music/repositories/redis/**'] -> included
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[3] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[4] (IfElse)
┃ ┃ ┃ ┗ null ()
┃ ┃ ┃ ╺  Info Will replace [spring-music->tanzu-music]
┃ ┃ ┃ ╺  Info Will replace [JAVA_VERSION->21]
┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7] (Let)
┃ ┃ ┃ ┃ Debug Adding symbol uuid with value '1a8acfcc-0ae6-4a08-9144-0728733f1a8a'
┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in (Chain)
┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, Merge, UniquePath, Merge, UniquePath, Provenance)
┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[0].apply (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Select, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ Debug bin/main/com/example/music/repositories/mongodb/MongoAlbumRepository.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/app.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/errors.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/status.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/Album.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/fileHashes/fileHashes.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/ApplicationInfo.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/albums.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/Application.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/grid.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/ErrorController.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/dependencies-accessors/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/dependencies-accessors/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/fileChanges/last-build.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/RandomIdGenerator.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/footer.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/jpa/JpaAlbumRepository.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/config/data/RedisConfig.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/test/com/example/music/ApplicationTests.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileChanges/last-build.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/InfoController.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/tanzu-music.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/AlbumRepositoryPopulator.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/redis/RedisAlbumRepository.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/css/app.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings-white.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/status.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/errors.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/info.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/sha1-checksums.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/application.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/sha1-checksums.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/list.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/header.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/albums.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/css/multi-columns-row.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/checksums.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/index.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/checksums.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/AlbumController.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/albumForm.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/md5-checksums.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/albums.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/executionHistory/executionHistory.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug tanzu.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated (Chain)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Running Chain(ApplyTo, ApplyTo, ApplyTo, ApplyTo, ApplyTo)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[0].apply (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[1].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '<java.version>.*<' with '<java.version>21<'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[2].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex 'sourceCompatibility = .*' with 'sourceCompatibility ...(truncated)'
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[3].apply (ReplaceText)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗  Info Will replace regex '(?<unmodified>JavaVersion\.VERSION_)(\d+)' with '${unmodified}21'
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ ╺ engine.transformations[1].validated.transformations[7].in.transformations[1].sources[1].validated.transformations[4].apply (OpenRewriteRecipe)
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[2] (UniquePath)
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/repositories/mongodb/MongoAlbumRepository.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitattributes', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/misc.xml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/status.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/js/app.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/workspace.xml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/gradle.xml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/errors.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/status.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/domain/Album.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/domain/ApplicationInfo.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/fileHashes/fileHashes.lock', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/status.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/albums.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/Application.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/vcs-1/gc.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/AlbumController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/grid.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/web/ErrorController.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/footer.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/errors.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/InfoController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/dependencies-accessors/gc.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/dependencies-accessors/gc.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/css/app.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/albumForm.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/list.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/cloudfoundry/manifest.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/fileChanges/last-build.bin', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'gradle.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/img/glyphicons-halflings.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/domain/RandomIdGenerator.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/fileHashes/fileHashes.bin', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/web/ErrorController.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'tanzu.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/application.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/img/glyphicons-halflings.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/Album.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/header.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/buildOutputCleanup.lock', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/gc.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/footer.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/fileHashes/fileHashes.lock', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/app.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/config/data/RedisConfig.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/repositories/jpa/JpaAlbumRepository.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/buildOutputCleanup/cache.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/test/com/example/music/ApplicationTests.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'LICENSE', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/test/java/com/example/music/ApplicationTests.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/ApplicationInfo.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/fileChanges/last-build.bin', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/web/InfoController.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/errors.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.tanzu/config/tanzu-music.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/Application.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.idea/.gitignore', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/kubernetes/service.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'README.md', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/repositories/AlbumRepositoryPopulator.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/index.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/css/app.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/repositories/redis/RedisAlbumRepository.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/img/glyphicons-halflings-white.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/domain/RandomIdGenerator.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/js/status.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/js/errors.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/js/info.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gitignore', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/cloudfoundry/project.toml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/checksums/sha1-checksums.bin', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/albums.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/grid.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/application.yml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/checksums/sha1-checksums.bin', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/js/info.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/list.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/header.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'build.gradle', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/img/glyphicons-halflings-white.png', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'deploy/kubernetes/deployment.yaml', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/js/albums.js', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/css/multi-columns-row.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'settings.gradle', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/gc.properties', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/albums.json', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.vscode/settings.json', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/checksums/checksums.lock', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/index.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/checksums/checksums.lock', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/com/example/music/web/AlbumController.class', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/static/templates/albumForm.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'bin/main/albums.json', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.8/checksums/md5-checksums.bin', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path 'src/main/resources/static/templates/albums.html', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┃ Debug Multiple representations for path '.gradle/8.9/executionHistory/executionHistory.lock', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┗ Debug Multiple representations for path 'src/main/resources/static/css/multi-columns-row.css', will use the one appearing last 
┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3] (Merge)
┃ ┃ ┃ ┃ ┃ ┃  Info Running Merge(Select, InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┏ Debug bin/main/com/example/music/repositories/mongodb/MongoAlbumRepository.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/app.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/errors.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/status.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/Album.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/ApplicationInfo.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/fileHashes/fileHashes.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/albums.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/Application.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/grid.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/ErrorController.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/dependencies-accessors/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/dependencies-accessors/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/fileChanges/last-build.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/RandomIdGenerator.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tanzu.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/footer.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/config/data/RedisConfig.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/jpa/JpaAlbumRepository.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/test/com/example/music/ApplicationTests.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileChanges/last-build.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/InfoController.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/tanzu-music.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/AlbumRepositoryPopulator.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/css/app.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/redis/RedisAlbumRepository.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings-white.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/status.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/errors.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/info.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/sha1-checksums.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/application.yml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/sha1-checksums.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/list.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/header.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/albums.js matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/css/multi-columns-row.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/gc.properties matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/checksums.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/index.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/checksums.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/AlbumController.class matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/albumForm.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/albums.json matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/md5-checksums.bin matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/executionHistory/executionHistory.lock matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┗ Debug src/main/resources/static/css/multi-columns-row.css matched ['**'] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1] (InvokeFragment)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┏ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1].validated (IfElse)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ engine.transformations[1].validated.transformations[7].in.transformations[3].sources[1].validated.then (Include)
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  Info Will include [gradlew*, gradle/**]
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/mongodb/MongoAlbumRepository.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitattributes didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/misc.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/status.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/app.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/workspace.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/gradle.xml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/errors.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/status.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/Album.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/ApplicationInfo.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/fileHashes/fileHashes.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/status.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/albums.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/Application.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/vcs-1/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/AlbumController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/grid.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/ErrorController.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/footer.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/errors.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/InfoController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/dependencies-accessors/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/dependencies-accessors/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/app.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albumForm.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/list.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/manifest.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/fileChanges/last-build.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/domain/RandomIdGenerator.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/web/ErrorController.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug tanzu.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/application.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/Album.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/header.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/buildOutputCleanup.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/footer.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/jpa/JpaAlbumRepository.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileHashes/fileHashes.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/app.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/config/data/RedisConfig.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/jpa/JpaAlbumRepository.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/buildOutputCleanup/cache.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/test/com/example/music/ApplicationTests.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug LICENSE didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/test/java/com/example/music/ApplicationTests.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/ApplicationInfo.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/fileChanges/last-build.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/InfoController.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/errors.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .tanzu/config/tanzu-music.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/Application.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .idea/.gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/service.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/AlbumRepositoryPopulator.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/index.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/css/app.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/repositories/redis/RedisAlbumRepository.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/img/glyphicons-halflings-white.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/domain/RandomIdGenerator.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/status.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/errors.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/info.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gitignore didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/cloudfoundry/project.toml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/sha1-checksums.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/albums.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/grid.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/application.yml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/sha1-checksums.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/js/info.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/list.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/header.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug build.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/img/glyphicons-halflings-white.png didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug deploy/kubernetes/deployment.yaml didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/js/albums.js didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/css/multi-columns-row.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug settings.gradle didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/gc.properties didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/albums.json didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .vscode/settings.json didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/checksums.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/index.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/checksums/checksums.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/java/com/example/music/repositories/AlbumRepositoryPopulator.java didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/com/example/music/web/AlbumController.class didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/static/templates/albumForm.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug bin/main/albums.json didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.8/checksums/md5-checksums.bin didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/templates/albums.html didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug .gradle/8.9/executionHistory/executionHistory.lock didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug src/main/resources/static/css/multi-columns-row.css didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug README.md didn't match [gradlew*, gradle/**] -> excluded
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.jar matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradle/wrapper/gradle-wrapper.properties matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ Debug gradlew matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ┗ ┗ ┗ Debug gradlew.bat matched [gradlew*, gradle/**] -> included
┃ ┃ ┃ ┃ ┃ ╺ engine.transformations[1].validated.transformations[7].in.transformations[4] (UniquePath)
┃ ┗ ┗ ┗ ┗ ╺ engine.transformations[1].validated.transformations[7].in.transformations[5] (Provenance)
┗ ╺ engine.transformations[2] (UniquePath)
```
