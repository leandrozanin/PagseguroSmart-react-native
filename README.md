# PagseguroSmart-react-native
Integração da smart pos com react native

# Adicionando Dependencias
build.gradle
{
   ext {
          kotlinVersion = '1.3.21'
      }
    repositories {
          maven {
              url 'https://github.com/pagseguro/PlugPagServiceWrapper/raw/master'
          }
    }
  dependencies {
      implementation "org.jetbrains.kotlin:kotlin-stdlib-jdk7:${project.ext.kotlinVersion}"
      implementation 'br.com.uol.pagseguro.plugpagservice.wrapper:wrapper:1.5.0'
  }
}    
