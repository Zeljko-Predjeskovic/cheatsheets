# Asciidoc Cheatsheet

This repo has a pom file and an asciidoc cheatsheet. In the maven project copy the pom file,
create a src/docs/asciidoc folder where you put your adoc files into it.

I manage my doc with maven, but if you don't want to use mavem, you have also npm.

## To generate the asciidoc to pdf, just do maven clean and install

    mvn clean install

    mvn install

## If you want asciidoc into a revealjs presentation, just comment the xml backend and attributes out

     <configuration>
        <backend>pdf</backend>
             <!-- <backend>revealjs</backend>-->

                <!--<attributes>
                    <imagesdir>./images</imagesdir>
                        <source-highlighter>coderay</source-highlighter>
                        <icons>font</icons>
                        <pagenums/>
                        <toc/>
                        <idprefix/>
                        <idseparator>-</idseparator>
                       <revealjsdir>
                            https://cdn.jsdelivr.net/npm/reveal.js@3.9.2
                        </revealjsdir>
                </attributes>-->
        </configuration>
