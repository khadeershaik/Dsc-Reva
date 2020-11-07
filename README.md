f_groceries/.gitignore
.DS_Store
.dart_tool/

.packages
.pub/

build/

.flutter-plugins
<component name="ProjectCodeStyleConfiguration">
  <code_scheme name="Project" version="173">
    <Objective-C-extensions>
      <file>
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Import" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Macro" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Typedef" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Enum" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Constant" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Global" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Struct" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="FunctionPredecl" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Function" />
      </file>
      <class>
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Property" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="Synthesize" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="InitMethod" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="StaticMethod" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="InstanceMethod" />
        <option name="com.jetbrains.cidr.lang.util.OCDeclarationKind" value="DeallocMethod" />
      </class>
      <extensions>
        <pair source="cpp" header="h" fileNamingConvention="NONE" />
        <pair source="c" header="h" fileNamingConvention="NONE" />
      </extensions>
    </Objective-C-extensions>
  </code_scheme>
</component> 
<component name="libraryTable">
  <library name="Flutter Plugins" type="FlutterPluginsLibraryType">
    <CLASSES />
    <JAVADOC />
    <SOURCES />
  </library>
</component> 
<component name="libraryTable">
  <library name="Flutter for Android">
    <CLASSES>
      <root url="jar:///home/imperial-web1/flutter/bin/cache/artifacts/engine/android-arm/flutter.jar!/" />
    </CLASSES>
    <JAVADOC />
    <SOURCES />
  </library>
</component>
<?xml version="1.0" encoding="UTF-8"?>
<project version="4">
  <component name="NullableNotNullManager">
    <option name="myDefaultNullable" value="android.support.annotation.Nullable" />
    <option name="myDefaultNotNull" value="android.support.annotation.NonNull" />
    <option name="myNullables">
      <value>
        <list size="5">
          <item index="0" class="java.lang.String" itemvalue="org.jetbrains.annotations.Nullable" />
          <item index="1" class="java.lang.String" itemvalue="javax.annotation.Nullable" />
          <item index="2" class="java.lang.String" itemvalue="javax.annotation.CheckForNull" />
          <item index="3" class="java.lang.String" itemvalue="edu.umd.cs.findbugs.annotations.Nullable" />
          <item index="4" class="java.lang.String" itemvalue="android.support.annotation.Nullable" />
        </list>
      </value>
    </option>
    <option name="myNotNulls">
      <value>
        <list size="4">
          <item index="0" class="java.lang.String" itemvalue="org.jetbrains.annotations.NotNull" />
          <item index="1" class="java.lang.String" itemvalue="javax.annotation.Nonnull" />
          <item index="2" class="java.lang.String" itemvalue="edu.umd.cs.findbugs.annotations.NonNull" />
          <item index="3" class="java.lang.String" itemvalue="android.support.annotation.NonNull" />
        </list>
      </value>
    </option>
  </component>
</project> 
<?xml version="1.0" encoding="UTF-8"?>
<project version="4">
  <component name="ProjectModuleManager">
    <modules>
      <module fileurl="file://$PROJECT_DIR$/f_groceries.iml" filepath="$PROJECT_DIR$/f_groceries.iml" />
      <module fileurl="file://$PROJECT_DIR$/f_groceries_android.iml" filepath="$PROJECT_DIR$/f_groceries_android.iml" />
    </modules>
  </component>
</project>
<component name="ProjectRunConfigurationManager">
  <configuration default="false" name="main.dart" type="FlutterRunConfigurationType" factoryName="Flutter">
    <option name="filePath" value="$PROJECT_DIR$/lib/main.dart" />
    <method />
  </configuration>
</component> 
# This file tracks properties of this Flutter project.
# Used by Flutter tool to assess capabilities and perform upgrades etc.
#
# This file should be version controlled and should not be manually edited.

version:
  revision: 5ab9e70727d858def3a586db7fb98ee580352957
  channel: beta
# f_groceries

A new Flutter application.

## Getting Started

For help getting started with Flutter, view our online
[documentation](https://flutter.io/).
<?xml version="1.0" encoding="UTF-8"?>
<module type="JAVA_MODULE" version="4">
  <component name="NewModuleRootManager" inherit-compiler-output="true">
    <exclude-output />
    <content url="file://$MODULE_DIR$/android">
      <sourceFolder url="file://$MODULE_DIR$/android/app/src/main/java" isTestSource="false" />
    </content>
    <orderEntry type="jdk" jdkName="Android API 25 Platform" jdkType="Android SDK" />
    <orderEntry type="sourceFolder" forTests="false" />
    <orderEntry type="library" name="Flutter for Android" level="project" />
  </component>
</module>
*.iml
*.class
.gradle
/local.properties
/.idea/workspace.xml
/.idea/libraries
.DS_Store
/build
/captures
GeneratedPluginRegistrant.java
def localProperties = new Properties()
def localPropertiesFile = rootProject.file('local.properties')
if (localPropertiesFile.exists()) {
    localPropertiesFile.withReader('UTF-8') { reader ->
        localProperties.load(reader)
    }
}

def flutterRoot = localProperties.getProperty('flutter.sdk')
if (flutterRoot == null) {
    throw new GradleException("Flutter SDK not found. Define location with flutter.sdk in the local.properties file.")
}

def flutterVersionCode = localProperties.getProperty('flutter.versionCode')
if (flutterVersionCode == null) {
    flutterVersionCode = '1'
}

def flutterVersionName = localProperties.getProperty('flutter.versionName')
if (flutterVersionName == null) {
    flutterVersionName = '1.0'
}

apply plugin: 'com.android.application'
apply from: "$flutterRoot/packages/flutter_tools/gradle/flutter.gradle"

android {
    compileSdkVersion 27

    lintOptions {
        disable 'InvalidPackage'
    }

    defaultConfig {
        // TODO: Specify your own unique Application ID (https://developer.android.com/studio/build/application-id.html).
        applicationId "com.imperialinfosys.fgroceries"
        minSdkVersion 16
        targetSdkVersion 27
        versionCode flutterVersionCode.toInteger()
        versionName flutterVersionName
        testInstrumentationRunner "android.support.test.runner.AndroidJUnitRunner"
    }

    buildTypes {
        release {
            // TODO: Add your own signing config for the release build.
            // Signing with the debug keys for now, so `flutter run --release` works.
            signingConfig signingConfigs.debug
        }
    }
}

flutter {
    source '../..'
}

dependencies {
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'com.android.support.test:runner:1.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2'
}
<manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.imperialinfosys.fgroceries">

    <!-- The INTERNET permission is required for development. Specifically,
         flutter needs it to communicate with the running application
         to allow setting breakpoints, to provide hot reload, etc.
    -->
    <uses-permission android:name="android.permission.INTERNET"/>

    <!-- io.flutter.app.FlutterApplication is an android.app.Application that
         calls FlutterMain.startInitialization(this); in its onCreate method.
         In most cases you can leave this as-is, but you if you want to provide
         additional functionality it is fine to subclass or reimplement
         FlutterApplication and put your custom class here. -->
    <application
        android:name="io.flutter.app.FlutterApplication"
        android:label="f_groceries"
        android:icon="@mipmap/ic_launcher">
        <activity
            android:name=".MainActivity"
            android:launchMode="singleTop"
            android:theme="@style/LaunchTheme"
            android:configChanges="orientation|keyboardHidden|keyboard|screenSize|locale|layoutDirection|fontScale|screenLayout|density"
            android:hardwareAccelerated="true"
            android:windowSoftInputMode="adjustResize">
            <!-- This keeps the window background of the activity showing
                 until Flutter renders its first frame. It can be removed if
                 there is no splash screen (such as the default splash screen
                 defined in @style/LaunchTheme). -->
            <meta-data
                android:name="io.flutter.app.android.SplashScreenUntilFirstFrame"
                android:value="true" />
            <intent-filter>
                <action android:name="android.intent.action.MAIN"/>
                <category android:name="android.intent.category.LAUNCHER"/>
            </intent-filter>
        </activity>
    </application>
</manifest>
package com.imperialinfosys.fgroceries;

import android.os.Bundle;
import io.flutter.app.FlutterActivity;
import io.flutter.plugins.GeneratedPluginRegistrant;

public class MainActivity extends FlutterActivity {
  @Override
  protected void onCreate(Bundle savedInstanceState) {
    super.onCreate(savedInstanceState);
    GeneratedPluginRegistrant.registerWith(this);
  }
}
<?xml version="1.0" encoding="utf-8"?>
<!-- Modify this file to customize your launch splash screen -->
<layer-list xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:drawable="@android:color/white" />

    <!-- You can insert your own image assets here -->
    <!-- <item>
        <bitmap
            android:gravity="center"
            android:src="@mipmap/launch_image" />
    </item> -->
</layer-list>
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <style name="LaunchTheme" parent="@android:style/Theme.Black.NoTitleBar">
        <!-- Show a splash screen on the activity. Automatically removed when
             Flutter draws its first frame -->
        <item name="android:windowBackground">@drawable/launch_background</item>
    </style>
</resources>
buildscript {
    repositories {
        google()
        jcenter()
    }

    dependencies {
        classpath 'com.android.tools.build:gradle:3.1.2'
    }
}

allprojects {
    repositories {
        google()
        jcenter()
    }
}

rootProject.buildDir = '../build'
subprojects {
    project.buildDir = "${rootProject.buildDir}/${project.name}"
}
subprojects {
    project.evaluationDependsOn(':app')
}

task clean(type: Delete) {
    delete rootProject.buildDir
}
org.gradle.jvmargs=-Xmx1536M
#Fri Jun 23 08:50:38 CEST 2017
distributionBase=GRADLE_USER_HOME
distributionPath=wrapper/dists
zipStoreBase=GRADLE_USER_HOME
zipStorePath=wrapper/dists
distributionUrl=https\://services.gradle.org/distributions/gradle-4.4-all.zip
#!/usr/bin/env bash

##############################################################################
##
##  Gradle start up script for UN*X
##
##############################################################################

# Add default JVM options here. You can also use JAVA_OPTS and GRADLE_OPTS to pass JVM options to this script.
DEFAULT_JVM_OPTS=""

APP_NAME="Gradle"
APP_BASE_NAME=`basename "$0"`

# Use the maximum available, or set MAX_FD != -1 to use that value.
MAX_FD="maximum"

warn ( ) {
    echo "$*"
}

die ( ) {
    echo
    echo "$*"
    echo
    exit 1
}

# OS specific support (must be 'true' or 'false').
cygwin=false
msys=false
darwin=false
case "`uname`" in
  CYGWIN* )
    cygwin=true
    ;;
  Darwin* )
    darwin=true
    ;;
  MINGW* )
    msys=true
    ;;
esac

# Attempt to set APP_HOME
# Resolve links: $0 may be a link
PRG="$0"
# Need this for relative symlinks.
while [ -h "$PRG" ] ; do
    ls=`ls -ld "$PRG"`
    link=`expr "$ls" : '.*-> \(.*\)$'`
    if expr "$link" : '/.*' > /dev/null; then
        PRG="$link"
    else
        PRG=`dirname "$PRG"`"/$link"
    fi
done
SAVED="`pwd`"
cd "`dirname \"$PRG\"`/" >/dev/null
APP_HOME="`pwd -P`"
cd "$SAVED" >/dev/null

CLASSPATH=$APP_HOME/gradle/wrapper/gradle-wrapper.jar

# Determine the Java command to use to start the JVM.
if [ -n "$JAVA_HOME" ] ; then
    if [ -x "$JAVA_HOME/jre/sh/java" ] ; then
        # IBM's JDK on AIX uses strange locations for the executables
        JAVACMD="$JAVA_HOME/jre/sh/java"
    else
        JAVACMD="$JAVA_HOME/bin/java"
    fi
    if [ ! -x "$JAVACMD" ] ; then
        die "ERROR: JAVA_HOME is set to an invalid directory: $JAVA_HOME
Please set the JAVA_HOME variable in your environment to match the
location of your Java installation."
    fi
else
    JAVACMD="java"
    which java >/dev/null 2>&1 || die "ERROR: JAVA_HOME is not set and no 'java' command could be found in your PATH.
Please set the JAVA_HOME variable in your environment to match the
location of your Java installation."
fi

# Increase the maximum file descriptors if we can.
if [ "$cygwin" = "false" -a "$darwin" = "false" ] ; then
    MAX_FD_LIMIT=`ulimit -H -n`
    if [ $? -eq 0 ] ; then
        if [ "$MAX_FD" = "maximum" -o "$MAX_FD" = "max" ] ; then
            MAX_FD="$MAX_FD_LIMIT"
        fi
        ulimit -n $MAX_FD
        if [ $? -ne 0 ] ; then
            warn "Could not set maximum file descriptor limit: $MAX_FD"
        fi
    else
        warn "Could not query maximum file descriptor limit: $MAX_FD_LIMIT"
    fi
fi

# For Darwin, add options to specify how the application appears in the dock
if $darwin; then
    GRADLE_OPTS="$GRADLE_OPTS \"-Xdock:name=$APP_NAME\" \"-Xdock:icon=$APP_HOME/media/gradle.icns\""
fi

# For Cygwin, switch paths to Windows format before running java
if $cygwin ; then
    APP_HOME=`cygpath --path --mixed "$APP_HOME"`
    CLASSPATH=`cygpath --path --mixed "$CLASSPATH"`
    JAVACMD=`cygpath --unix "$JAVACMD"`

    # We build the pattern for arguments to be converted via cygpath
    ROOTDIRSRAW=`find -L / -maxdepth 1 -mindepth 1 -type d 2>/dev/null`
    SEP=""
    for dir in $ROOTDIRSRAW ; do
        ROOTDIRS="$ROOTDIRS$SEP$dir"
        SEP="|"
    done
    OURCYGPATTERN="(^($ROOTDIRS))"
    # Add a user-defined pattern to the cygpath arguments
    if [ "$GRADLE_CYGPATTERN" != "" ] ; then
        OURCYGPATTERN="$OURCYGPATTERN|($GRADLE_CYGPATTERN)"
    fi
    # Now convert the arguments - kludge to limit ourselves to /bin/sh
    i=0
    for arg in "$@" ; do
        CHECK=`echo "$arg"|egrep -c "$OURCYGPATTERN" -`
        CHECK2=`echo "$arg"|egrep -c "^-"`                                 ### Determine if an option

        if [ $CHECK -ne 0 ] && [ $CHECK2 -eq 0 ] ; then                    ### Added a condition
            eval `echo args$i`=`cygpath --path --ignore --mixed "$arg"`
        else
            eval `echo args$i`="\"$arg\""
        fi
        i=$((i+1))
    done
    case $i in
        (0) set -- ;;
        (1) set -- "$args0" ;;
        (2) set -- "$args0" "$args1" ;;
        (3) set -- "$args0" "$args1" "$args2" ;;
        (4) set -- "$args0" "$args1" "$args2" "$args3" ;;
        (5) set -- "$args0" "$args1" "$args2" "$args3" "$args4" ;;
        (6) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" ;;
        (7) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" ;;
        (8) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" "$args7" ;;
        (9) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" "$args7" "$args8" ;;
    esac
fi

# Split up the JVM_OPTS And GRADLE_OPTS values into an array, following the shell quoting and substitution rules
function splitJvmOpts() {
    JVM_OPTS=("$@")
}
eval splitJvmOpts $DEFAULT_JVM_OPTS $JAVA_OPTS $GRADLE_OPTS
JVM_OPTS[${#JVM_OPTS[*]}]="-Dorg.gradle.appname=$APP_BASE_NAME"

exec "$JAVACMD" "${JVM_OPTS[@]}" -classpath "$CLASSPATH" org.gradle.wrapper.GradleWrapperMain "$@"
@if "%DEBUG%" == "" @echo off
@rem ##########################################################################
@rem
@rem  Gradle startup script for Windows
@rem
@rem ##########################################################################

@rem Set local scope for the variables with windows NT shell
if "%OS%"=="Windows_NT" setlocal

@rem Add default JVM options here. You can also use JAVA_OPTS and GRADLE_OPTS to pass JVM options to this script.
set DEFAULT_JVM_OPTS=

set DIRNAME=%~dp0
if "%DIRNAME%" == "" set DIRNAME=.
set APP_BASE_NAME=%~n0
set APP_HOME=%DIRNAME%

@rem Find java.exe
if defined JAVA_HOME goto findJavaFromJavaHome

set JAVA_EXE=java.exe
%JAVA_EXE% -version >NUL 2>&1
if "%ERRORLEVEL%" == "0" goto init

echo.
echo ERROR: JAVA_HOME is not set and no 'java' command could be found in your PATH.
echo.
echo Please set the JAVA_HOME variable in your environment to match the
echo location of your Java installation.

goto fail

:findJavaFromJavaHome
set JAVA_HOME=%JAVA_HOME:"=%
set JAVA_EXE=%JAVA_HOME%/bin/java.exe

if exist "%JAVA_EXE%" goto init

echo.
echo ERROR: JAVA_HOME is set to an invalid directory: %JAVA_HOME%
echo.
echo Please set the JAVA_HOME variable in your environment to match the
echo location of your Java installation.

goto fail

:init
@rem Get command-line arguments, handling Windowz variants

if not "%OS%" == "Windows_NT" goto win9xME_args
if "%@eval[2+2]" == "4" goto 4NT_args

:win9xME_args
@rem Slurp the command line arguments.
set CMD_LINE_ARGS=
set _SKIP=2

:win9xME_args_slurp
if "x%~1" == "x" goto execute

set CMD_LINE_ARGS=%*
goto execute

:4NT_args
@rem Get arguments from the 4NT Shell from JP Software
set CMD_LINE_ARGS=%$

:execute
@rem Setup the command line

set CLASSPATH=%APP_HOME%\gradle\wrapper\gradle-wrapper.jar

@rem Execute Gradle
"%JAVA_EXE%" %DEFAULT_JVM_OPTS% %JAVA_OPTS% %GRADLE_OPTS% "-Dorg.gradle.appname=%APP_BASE_NAME%" -classpath "%CLASSPATH%" org.gradle.wrapper.GradleWrapperMain %CMD_LINE_ARGS%

:end
@rem End local scope for the variables with windows NT shell
if "%ERRORLEVEL%"=="0" goto mainEnd

:fail
rem Set variable GRADLE_EXIT_CONSOLE if you need the _script_ return code instead of
rem the _cmd.exe /c_ return code!
if  not "" == "%GRADLE_EXIT_CONSOLE%" exit 1
exit /b 1

:mainEnd
if "%OS%"=="Windows_NT" endlocal

:omega
include ':app'

def flutterProjectRoot = rootProject.projectDir.parentFile.toPath()

def plugins = new Properties()
def pluginsFile = new File(flutterProjectRoot.toFile(), '.flutter-plugins')
if (pluginsFile.exists()) {
    pluginsFile.withReader('UTF-8') { reader -> plugins.load(reader) }
}

plugins.each { name, path ->
    def pluginDirectory = flutterProjectRoot.resolve(path).resolve('android').toFile()
    include ":$name"
    project(":$name").projectDir = pluginDirectory
}
{
  "status": 200,
  "message": "Commodity List Found",
  "data": [
    {
      "id": "1",
      "name": "Balbhadrasinh parmar",
      "mobilenumber": "9974619782",
      "address": "61 Rajputfali ",
      "city": "vadagam",
      "distric": "Arvalli",
      "state": "Gujarat",
      "pincode": "383307"
    },
    {
      "id": "1",
      "name": "Balbhadrasinh parmar",
      "mobilenumber": "9974619782",
      "address": "61 Rajputfali ",
      "city": "vadagam",
      "distric": "Arvalli",
      "state": "Gujarat",
      "pincode": "383307"
    },
    {
      "id": "1",
      "name": "Balbhadrasinh parmar",
      "mobilenumber": "9974619782",
      "address": "61 Rajputfali ",
      "city": "vadagam",
      "distric": "Arvalli",
      "state": "Gujarat",
      "pincode": "383307"
    }
  ]
} 
<?xml version="1.0" encoding="UTF-8"?>
<module type="JAVA_MODULE" version="4">
  <component name="NewModuleRootManager" inherit-compiler-output="true">
    <exclude-output />
    <content url="file://$MODULE_DIR$">
      <sourceFolder url="file://$MODULE_DIR$/lib" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/test" isTestSource="true" />
      <excludeFolder url="file://$MODULE_DIR$/.dart_tool" />
      <excludeFolder url="file://$MODULE_DIR$/.idea" />
      <excludeFolder url="file://$MODULE_DIR$/.pub" />
      <excludeFolder url="file://$MODULE_DIR$/build" />
    </content>
    <orderEntry type="sourceFolder" forTests="false" />
    <orderEntry type="library" name="Dart SDK" level="project" />
    <orderEntry type="library" name="Flutter Plugins" level="project" />
    <orderEntry type="library" name="Dart Packages" level="project" />
  </component>
</module> 
<?xml version="1.0" encoding="UTF-8"?>
<module type="JAVA_MODULE" version="4">
  <component name="FacetManager">
    <facet type="android" name="Android">
      <configuration>
        <option name="ALLOW_USER_CONFIGURATION" value="false" />
        <option name="GEN_FOLDER_RELATIVE_PATH_APT" value="/android/gen" />
        <option name="GEN_FOLDER_RELATIVE_PATH_AIDL" value="/android/gen" />
        <option name="MANIFEST_FILE_RELATIVE_PATH" value="/android/AndroidManifest.xml" />
        <option name="RES_FOLDER_RELATIVE_PATH" value="/android/res" />
        <option name="ASSETS_FOLDER_RELATIVE_PATH" value="/android/assets" />
        <option name="LIBS_FOLDER_RELATIVE_PATH" value="/android/libs" />
        <option name="PROGUARD_LOGS_FOLDER_RELATIVE_PATH" value="/android/proguard_logs" />
      </configuration>
    </facet>
  </component>
  <component name="NewModuleRootManager" inherit-compiler-output="true">
    <exclude-output />
    <content url="file://$MODULE_DIR$/android">
      <sourceFolder url="file://$MODULE_DIR$/android/app/src/main/java" isTestSource="false" />
      <sourceFolder url="file://$MODULE_DIR$/android/gen" isTestSource="false" generated="true" />
    </content>
    <orderEntry type="jdk" jdkName="Android API 25 Platform" jdkType="Android SDK" />
    <orderEntry type="sourceFolder" forTests="false" />
    <orderEntry type="library" name="Flutter for Android" level="project" />
  </component>
</module>
.idea/
.vagrant/
.sconsign.dblite
.svn/

.DS_Store
*.swp
profile

DerivedData/
build/
GeneratedPluginRegistrant.h
GeneratedPluginRegistrant.m

.generated/

*.pbxuser
*.mode1v3
*.mode2v3
*.perspectivev3

!default.pbxuser
!default.mode1v3
!default.mode2v3
!default.perspectivev3

xcuserdata

*.moved-aside

*.pyc
*sync/
Icon?
.tags*

/Flutter/app.flx
/Flutter/app.zip
/Flutter/flutter_assets/
/Flutter/App.framework
/Flutter/Flutter.framework
/Flutter/Generated.xcconfig
/ServiceDefinitions.json

Pods/
.symlinks/
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
  <key>CFBundleDevelopmentRegion</key>
  <string>en</string>
  <key>CFBundleExecutable</key>
  <string>App</string>
  <key>CFBundleIdentifier</key>
  <string>io.flutter.flutter.app</string>
  <key>CFBundleInfoDictionaryVersion</key>
  <string>6.0</string>
  <key>CFBundleName</key>
  <string>App</string>
  <key>CFBundlePackageType</key>
  <string>FMWK</string>
  <key>CFBundleShortVersionString</key>
  <string>1.0</string>
  <key>CFBundleSignature</key>
  <string>????</string>
  <key>CFBundleVersion</key>
  <string>1.0</string>
  <key>MinimumOSVersion</key>
  <string>8.0</string>
</dict>
</plist>
#include "Generated.xcconfig"
#include "Generated.xcconfig"
<?xml version="1.0" encoding="UTF-8"?>
<Scheme
   LastUpgradeVersion = "0910"
   version = "1.3">
   <BuildAction
      parallelizeBuildables = "YES"
      buildImplicitDependencies = "YES">
      <BuildActionEntries>
         <BuildActionEntry
            buildForTesting = "YES"
            buildForRunning = "YES"
            buildForProfiling = "YES"
            buildForArchiving = "YES"
            buildForAnalyzing = "YES">
            <BuildableReference
               BuildableIdentifier = "primary"
               BlueprintIdentifier = "97C146ED1CF9000F007C117D"
               BuildableName = "Runner.app"
               BlueprintName = "Runner"
               ReferencedContainer = "container:Runner.xcodeproj">
            </BuildableReference>
         </BuildActionEntry>
      </BuildActionEntries>
   </BuildAction>
   <TestAction
      buildConfiguration = "Debug"
      selectedDebuggerIdentifier = "Xcode.DebuggerFoundation.Debugger.LLDB"
      selectedLauncherIdentifier = "Xcode.DebuggerFoundation.Launcher.LLDB"
      language = ""
      shouldUseLaunchSchemeArgsEnv = "YES">
      <Testables>
      </Testables>
      <MacroExpansion>
         <BuildableReference
            BuildableIdentifier = "primary"
            BlueprintIdentifier = "97C146ED1CF9000F007C117D"
            BuildableName = "Runner.app"
            BlueprintName = "Runner"
            ReferencedContainer = "container:Runner.xcodeproj">
         </BuildableReference>
      </MacroExpansion>
      <AdditionalOptions>
      </AdditionalOptions>
   </TestAction>
   <LaunchAction
      buildConfiguration = "Debug"
      selectedDebuggerIdentifier = "Xcode.DebuggerFoundation.Debugger.LLDB"
      selectedLauncherIdentifier = "Xcode.DebuggerFoundation.Launcher.LLDB"
      language = ""
      launchStyle = "0"
      useCustomWorkingDirectory = "NO"
      ignoresPersistentStateOnLaunch = "NO"
      debugDocumentVersioning = "YES"
      debugServiceExtension = "internal"
      allowLocationSimulation = "YES">
      <BuildableProductRunnable
         runnableDebuggingMode = "0">
         <BuildableReference
            BuildableIdentifier = "primary"
            BlueprintIdentifier = "97C146ED1CF9000F007C117D"
            BuildableName = "Runner.app"
            BlueprintName = "Runner"
            ReferencedContainer = "container:Runner.xcodeproj">
         </BuildableReference>
      </BuildableProductRunnable>
      <AdditionalOptions>
      </AdditionalOptions>
   </LaunchAction>
   <ProfileAction
      buildConfiguration = "Release"
      shouldUseLaunchSchemeArgsEnv = "YES"
      savedToolIdentifier = ""
      useCustomWorkingDirectory = "NO"
      debugDocumentVersioning = "YES">
      <BuildableProductRunnable
         runnableDebuggingMode = "0">
         <BuildableReference
            BuildableIdentifier = "primary"
            BlueprintIdentifier = "97C146ED1CF9000F007C117D"
            BuildableName = "Runner.app"
            BlueprintName = "Runner"
            ReferencedContainer = "container:Runner.xcodeproj">
         </BuildableReference>
      </BuildableProductRunnable>
   </ProfileAction>
   <AnalyzeAction
      buildConfiguration = "Debug">
   </AnalyzeAction>
   <ArchiveAction
      buildConfiguration = "Release"
      revealArchiveInOrganizer = "YES">
   </ArchiveAction>
</Scheme>
#import <Flutter/Flutter.h>
#import <UIKit/UIKit.h>

@interface AppDelegate : FlutterAppDelegate

@end
#include "AppDelegate.h"
#include "GeneratedPluginRegistrant.h"

@implementation AppDelegate

- (BOOL)application:(UIApplication *)application
    didFinishLaunchingWithOptions:(NSDictionary *)launchOptions {
  [GeneratedPluginRegistrant registerWithRegistry:self];
  // Override point for customization after application launch.
  return [super application:application didFinishLaunchingWithOptions:launchOptions];
}

@end
{
  "images" : [
    {
      "size" : "20x20",
      "idiom" : "iphone",
      "filename" : "Icon-App-20x20@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "20x20",
      "idiom" : "iphone",
      "filename" : "Icon-App-20x20@3x.png",
      "scale" : "3x"
    },
    {
      "size" : "29x29",
      "idiom" : "iphone",
      "filename" : "Icon-App-29x29@1x.png",
      "scale" : "1x"
    },
    {
      "size" : "29x29",
      "idiom" : "iphone",
      "filename" : "Icon-App-29x29@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "29x29",
      "idiom" : "iphone",
      "filename" : "Icon-App-29x29@3x.png",
      "scale" : "3x"
    },
    {
      "size" : "40x40",
      "idiom" : "iphone",
      "filename" : "Icon-App-40x40@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "40x40",
      "idiom" : "iphone",
      "filename" : "Icon-App-40x40@3x.png",
      "scale" : "3x"
    },
    {
      "size" : "60x60",
      "idiom" : "iphone",
      "filename" : "Icon-App-60x60@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "60x60",
      "idiom" : "iphone",
      "filename" : "Icon-App-60x60@3x.png",
      "scale" : "3x"
    },
    {
      "size" : "20x20",
      "idiom" : "ipad",
      "filename" : "Icon-App-20x20@1x.png",
      "scale" : "1x"
    },
    {
      "size" : "20x20",
      "idiom" : "ipad",
      "filename" : "Icon-App-20x20@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "29x29",
      "idiom" : "ipad",
      "filename" : "Icon-App-29x29@1x.png",
      "scale" : "1x"
    },
    {
      "size" : "29x29",
      "idiom" : "ipad",
      "filename" : "Icon-App-29x29@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "40x40",
      "idiom" : "ipad",
      "filename" : "Icon-App-40x40@1x.png",
      "scale" : "1x"
    },
    {
      "size" : "40x40",
      "idiom" : "ipad",
      "filename" : "Icon-App-40x40@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "76x76",
      "idiom" : "ipad",
      "filename" : "Icon-App-76x76@1x.png",
      "scale" : "1x"
    },
    {
      "size" : "76x76",
      "idiom" : "ipad",
      "filename" : "Icon-App-76x76@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "83.5x83.5",
      "idiom" : "ipad",
      "filename" : "Icon-App-83.5x83.5@2x.png",
      "scale" : "2x"
    },
    {
      "size" : "1024x1024",
      "idiom" : "ios-marketing",
      "filename" : "Icon-App-1024x1024@1x.png",
      "scale" : "1x"
    }
  ],
  "info" : {
    "version" : 1,
    "author" : "xcode"
  }
}
{
  "images" : [
    {
      "idiom" : "universal",
      "filename" : "LaunchImage.png",
      "scale" : "1x"
    },
    {
      "idiom" : "universal",
      "filename" : "LaunchImage@2x.png",
      "scale" : "2x"
    },
    {
      "idiom" : "universal",
      "filename" : "LaunchImage@3x.png",
      "scale" : "3x"
    }
  ],
  "info" : {
    "version" : 1,
    "author" : "xcode"
  }
}
# Launch Screen Assets

You can customize the launch screen with your own desired assets by replacing the image files in this directory.

You can also do it by opening your Flutter project's Xcode project with `open ios/Runner.xcworkspace`, selecting `Runner/Assets.xcassets` in the Project Navigator and dropping in the desired images.
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<document type="com.apple.InterfaceBuilder3.CocoaTouch.Storyboard.XIB" version="3.0" toolsVersion="12121" systemVersion="16G29" targetRuntime="iOS.CocoaTouch" propertyAccessControl="none" useAutolayout="YES" launchScreen="YES" colorMatched="YES" initialViewController="01J-lp-oVM">
    <dependencies>
        <deployment identifier="iOS"/>
        <plugIn identifier="com.apple.InterfaceBuilder.IBCocoaTouchPlugin" version="12089"/>
    </dependencies>
    <scenes>
        <!--View Controller-->
        <scene sceneID="EHf-IW-A2E">
            <objects>
                <viewController id="01J-lp-oVM" sceneMemberID="viewController">
                    <layoutGuides>
                        <viewControllerLayoutGuide type="top" id="Ydg-fD-yQy"/>
                        <viewControllerLayoutGuide type="bottom" id="xbc-2k-c8Z"/>
                    </layoutGuides>
                    <view key="view" contentMode="scaleToFill" id="Ze5-6b-2t3">
                        <autoresizingMask key="autoresizingMask" widthSizable="YES" heightSizable="YES"/>
                        <subviews>
                            <imageView opaque="NO" clipsSubviews="YES" multipleTouchEnabled="YES" contentMode="center" image="LaunchImage" translatesAutoresizingMaskIntoConstraints="NO" id="YRO-k0-Ey4">
                            </imageView>
                        </subviews>
                        <color key="backgroundColor" red="1" green="1" blue="1" alpha="1" colorSpace="custom" customColorSpace="sRGB"/>
                        <constraints>
                            <constraint firstItem="YRO-k0-Ey4" firstAttribute="centerX" secondItem="Ze5-6b-2t3" secondAttribute="centerX" id="1a2-6s-vTC"/>
                            <constraint firstItem="YRO-k0-Ey4" firstAttribute="centerY" secondItem="Ze5-6b-2t3" secondAttribute="centerY" id="4X2-HB-R7a"/>
                        </constraints>
                    </view>
                </viewController>
                <placeholder placeholderIdentifier="IBFirstResponder" id="iYj-Kq-Ea1" userLabel="First Responder" sceneMemberID="firstResponder"/>
            </objects>
            <point key="canvasLocation" x="53" y="375"/>
        </scene>
    </scenes>
    <resources>
        <image name="LaunchImage" width="168" height="185"/>
    </resources>
</document>
<?xml version="1.0" encoding="UTF-8" standalone="no"?>
<document type="com.apple.InterfaceBuilder3.CocoaTouch.Storyboard.XIB" version="3.0" toolsVersion="10117" systemVersion="15F34" targetRuntime="iOS.CocoaTouch" propertyAccessControl="none" useAutolayout="YES" useTraitCollections="YES" initialViewController="BYZ-38-t0r">
    <dependencies>
        <deployment identifier="iOS"/>
        <plugIn identifier="com.apple.InterfaceBuilder.IBCocoaTouchPlugin" version="10085"/>
    </dependencies>
    <scenes>
        <!--Flutter View Controller-->
        <scene sceneID="tne-QT-ifu">
            <objects>
                <viewController id="BYZ-38-t0r" customClass="FlutterViewController" sceneMemberID="viewController">
                    <layoutGuides>
                        <viewControllerLayoutGuide type="top" id="y3c-jy-aDJ"/>
                        <viewControllerLayoutGuide type="bottom" id="wfy-db-euE"/>
                    </layoutGuides>
                    <view key="view" contentMode="scaleToFill" id="8bC-Xf-vdC">
                        <rect key="frame" x="0.0" y="0.0" width="600" height="600"/>
                        <autoresizingMask key="autoresizingMask" widthSizable="YES" heightSizable="YES"/>
                        <color key="backgroundColor" white="1" alpha="1" colorSpace="custom" customColorSpace="calibratedWhite"/>
                    </view>
                </viewController>
                <placeholder placeholderIdentifier="IBFirstResponder" id="dkx-z0-nzr" sceneMemberID="firstResponder"/>
            </objects>
        </scene>
    </scenes>
</document>
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
	<key>CFBundleDevelopmentRegion</key>
	<string>en</string>
	<key>CFBundleExecutable</key>
	<string>$(EXECUTABLE_NAME)</string>
	<key>CFBundleIdentifier</key>
	<string>$(PRODUCT_BUNDLE_IDENTIFIER)</string>
	<key>CFBundleInfoDictionaryVersion</key>
	<string>6.0</string>
	<key>CFBundleName</key>
	<string>f_groceries</string>
	<key>CFBundlePackageType</key>
	<string>APPL</string>
	<key>CFBundleShortVersionString</key>
	<string>$(FLUTTER_BUILD_NAME)</string>
	<key>CFBundleSignature</key>
	<string>????</string>
	<key>CFBundleVersion</key>
	<string>$(FLUTTER_BUILD_NUMBER)</string>
	<key>LSRequiresIPhoneOS</key>
	<true/>
	<key>UILaunchStoryboardName</key>
	<string>LaunchScreen</string>
	<key>UIMainStoryboardFile</key>
	<string>Main</string>
	<key>UISupportedInterfaceOrientations</key>
	<array>
		<string>UIInterfaceOrientationPortrait</string>
		<string>UIInterfaceOrientationLandscapeLeft</string>
		<string>UIInterfaceOrientationLandscapeRight</string>
	</array>
	<key>UISupportedInterfaceOrientations~ipad</key>
	<array>
		<string>UIInterfaceOrientationPortrait</string>
		<string>UIInterfaceOrientationPortraitUpsideDown</string>
		<string>UIInterfaceOrientationLandscapeLeft</string>
		<string>UIInterfaceOrientationLandscapeRight</string>
	</array>
	<key>UIViewControllerBasedStatusBarAppearance</key>
	<false/>
</dict>
</plist>
#import <Flutter/Flutter.h>
#import <UIKit/UIKit.h>
#import "AppDelegate.h"

int main(int argc, char* argv[]) {
  @autoreleasepool {
    return UIApplicationMain(argc, argv, nil, NSStringFromClass([AppDelegate class]));
  }
}
import 'package:flutter/material.dart';

class Patment extends StatefulWidget {
  @override
  State<StatefulWidget> createState() => payment();
}

class Item {
  final String itemName;
  final String itemQun;
  final String itemPrice;

  Item({this.itemName, this.itemQun, this.itemPrice});
}

class payment extends State<Patment> {
  final GlobalKey<ScaffoldState> _scaffoldKey = GlobalKey<ScaffoldState>();
  bool checkboxValueA = true;
  bool checkboxValueB = false;
  bool checkboxValueC = false;

  IconData _backIcon() {
    switch (Theme.of(context).platform) {
      case TargetPlatform.android:
      case TargetPlatform.fuchsia:
        return Icons.arrow_back;
      case TargetPlatform.iOS:
        return Icons.arrow_back_ios;
    }
    assert(false);
    return null;
  }
  int radioValue = 0;
  void handleRadioValueChanged(int value) {
    setState(() {
      radioValue = value;
    });
  }

  List<Item> itemList = <Item>[
    Item(itemName: 'Black Grape', itemQun: 'Qty:1', itemPrice: '\₹ 100'),
    Item(itemName: 'Tomato', itemQun: 'Qty:3', itemPrice: '\₹ 112'),
    Item(itemName: 'Mango', itemQun: 'Qty:2', itemPrice: '\₹ 105'),
    Item(itemName: 'Capsicum', itemQun: 'Qty:1', itemPrice: '\₹ 90'),
    Item(itemName: 'Lemon', itemQun: 'Qty:2', itemPrice: '\₹ 70'),
    Item(itemName: 'Apple', itemQun: 'Qty:1', itemPrice: '\₹ 50'),
  ];
  String toolbarname = 'CheckOut';

  @override
  Widget build(BuildContext context) {
    // TODO: implement build

    final double height = MediaQuery.of(context).size.height;

    AppBar appBar = AppBar(
      leading: IconButton(
        icon: Icon(_backIcon()),
        alignment: Alignment.centerLeft,
        tooltip: 'Back',
        onPressed: () {
          Navigator.pop(context);
        },
      ),
      title: Text(toolbarname),
      backgroundColor: Colors.white,
      actions: <Widget>[
        new Padding(
          padding: const EdgeInsets.all(10.0),
          child: new Container(
            height: 150.0,
            width: 30.0,
            child: new GestureDetector(
              onTap: () {
                /*Navigator.of(context).push(
                  new MaterialPageRoute(
                      builder:(BuildContext context) =>
                      new CartItemsScreen()
                  )
              );*/
              },
            ),
          ),
        )
      ],
    );

    return new Scaffold(
      key: _scaffoldKey,
      appBar: appBar,
      body: new Column(
        children: <Widget>[
          Container(
              margin: EdgeInsets.all(5.0),
              child: Card(
                  child: Container(
                      padding: const EdgeInsets.all(10.0),
                      child: Row(
                        mainAxisSize: MainAxisSize.max,
                        mainAxisAlignment: MainAxisAlignment.center,
                        children: <Widget>[
                          // three line description
                          Row(
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: <Widget>[
                              Padding(
                                padding: const EdgeInsets.only(bottom: 8.0),
                                child: Container(
                                    alignment: Alignment.center,
                                    child: Row(
                                      children: <Widget>[
                                        Text(
                                          'Delivery',
                                          style: TextStyle(
                                              fontSize: 18.0,
                                              fontWeight: FontWeight.bold,
                                              color: Colors.black38),
                                        ),
                                        IconButton(
                                            icon: Icon(
                                              Icons.play_circle_outline,
                                              color: Colors.black38,
                                            ),
                                            onPressed: null)
                                      ],
                                    )),
                              ),
                              Padding(
                                padding: const EdgeInsets.only(bottom: 8.0),
                                child: Container(
                                    alignment: Alignment.center,
                                    child: Row(
                                      children: <Widget>[
                                        Text(
                                          'Payment',
                                          style: TextStyle(
                                              fontSize: 18.0,
                                              fontWeight: FontWeight.bold,
                                              color: Colors.black),
                                        ),
                                        IconButton(
                                            icon: Icon(
                                              Icons.check_circle,
                                              color: Colors.blue,
                                            ),
                                            onPressed: null)
                                      ],
                                    )),
                              ),
                            ],
                          ),
                        ],
                      )))),
          _verticalDivider(),
          Container(
              margin: EdgeInsets.all(10.0),
              child: Card(
                child: Container(
                  color: Colors.green.shade100,
                  child: Container(
                      padding:
                          const EdgeInsets.fromLTRB(15.0, 15.0, 15.0, 15.0),
                      child: Text(
                          "GET EXTRA 5% OFF* with MONEY bank Simply Save Credit card. T&C.",
                          maxLines: 10,
                          style: TextStyle(
                              fontSize: 13.0, color: Colors.black87))),
                ),
              )),
          new Container(
            alignment: Alignment.topLeft,
            margin:
                EdgeInsets.only(left: 12.0, top: 5.0, right: 0.0, bottom: 5.0),
            child: new Text(
              'Payment Method',
              style: TextStyle(
                  color: Colors.black87,
                  fontWeight: FontWeight.bold,
                  fontSize: 18.0),
            ),
          ),
          _verticalDivider(),
          new Container(
              height: 264.0,
              margin: EdgeInsets.all(10.0),
              child: Card(
                child: Container(
                  child: Container(
                      child: Column(
                    children: <Widget>[
                      Container(
                        padding: EdgeInsets.only(left: 10.0),
                        child: Row(
                          mainAxisSize: MainAxisSize.max,
                          mainAxisAlignment: MainAxisAlignment.spaceBetween,
                          children: <Widget>[
                            Text("Wallet / UPI",
                                maxLines: 10,
                                style: TextStyle(
                                    fontSize: 15.0, color: Colors.black)),
                            Radio<int>(
                                value: 0,
                                groupValue: 0,
                                onChanged: null),
                          ],
                        ),
                      ),
                      Divider(),
                      _verticalD(),
                      Container(
                          padding: EdgeInsets.only(left: 10.0),
                          child: Row(
                            mainAxisSize: MainAxisSize.max,
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: <Widget>[
                              Text("Net Banking",
                                  maxLines: 10,
                                  style: TextStyle(
                                      fontSize: 15.0, color: Colors.black)),
                              Radio<int>(
                                  value: 0,
                                  groupValue: radioValue,
                                  onChanged: null),
                            ],
                          )),
                      Divider(),
                      _verticalD(),
                      Container(
                          padding: EdgeInsets.only(left: 10.0),
                          child: Row(
                            mainAxisSize: MainAxisSize.max,
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: <Widget>[
                              Text("Credit / Debit / ATM Card",
                                  maxLines: 10,
                                  style: TextStyle(
                                      fontSize: 15.0, color: Colors.black)),
                              Radio<int>(
                                  value: 0,
                                  groupValue: 0,
                                  onChanged: handleRadioValueChanged),
                            ],
                          )),
                      Divider(),
                      _verticalD(),
                      Container(
                          padding: EdgeInsets.only(left: 10.0),
                          child: Row(
                            mainAxisSize: MainAxisSize.max,
                            mainAxisAlignment: MainAxisAlignment.spaceBetween,
                            children: <Widget>[
                              Text("Cash on Delivery",
                                  maxLines: 10,
                                  style: TextStyle(
                                      fontSize: 15.0, color: Colors.black)),
                              Radio<int>(
                                  value: 0,
                                  groupValue: 0,
                                  onChanged: null),
                            ],
                          )),
                      Divider(),
                    ],
                  )),
                ),
              )),
          Container(
              alignment: Alignment.bottomLeft,
              height: 50.0,
              child: Card(
                child: Row(
                  mainAxisSize: MainAxisSize.max,
                  mainAxisAlignment: MainAxisAlignment.spaceBetween,
                  children: <Widget>[
                    IconButton(icon: Icon(Icons.info), onPressed: null),
                    Text(
                      'Total :',
                      style: TextStyle(
                          fontSize: 17.0,
                          color: Colors.black,
                          fontWeight: FontWeight.bold),
                    ),
                    Text(
                      '\₹ 524',
                      style: TextStyle(fontSize: 17.0, color: Colors.black54),
                    ),
                    Padding(
                      padding: const EdgeInsets.all(8.0),
                      child: Container(
                        alignment: Alignment.center,
                        child: OutlineButton(
                            borderSide: BorderSide(color: Colors.green),
                            child: const Text('PROCEED TO PAY'),
                            textColor: Colors.green,
                            onPressed: () {
                              //   Navigator.push(context, MaterialPageRoute(builder: (context)=> Item_Details()));
                            },
                            shape: new OutlineInputBorder(
                              borderRadius: BorderRadius.circular(30.0),
                            )),
                      ),
                    ),
                  ],
                ),
              )),
        ],
      ),
    );
  }

  _verticalDivider() => Container(
        padding: EdgeInsets.all(2.0),
      );

  _verticalD() => Container(
        margin: EdgeInsets.only(left: 5.0),
      );
}
import 'package:f_groceries/Cart_Screen.dart';
import 'package:f_groceries/item_details.dart';
import 'package:flutter/material.dart';
import 'package:flutter_range_slider/flutter_range_slider.dart';

class Help_Screen extends StatefulWidget {
  final String toolbarname;

  Help_Screen({Key key, this.toolbarname}) : super(key: key);

  @override
  State<StatefulWidget> createState() => Help(toolbarname);
}

class Help extends State<Help_Screen> {
  List list = ['12', '11'];

  bool switchValue = false;

  // String toolbarname = 'Fruiys & Vegetables';
  final GlobalKey<ScaffoldState> _scaffoldKey = GlobalKey<ScaffoldState>();
  String toolbarname;

  Help(this.toolbarname);

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    final ThemeData theme = Theme.of(context);
    final TextStyle dialogTextStyle =
    theme.textTheme.subhead.copyWith(color: theme.textTheme.caption.color);

    IconData _backIcon() {
      switch (Theme.of(context).platform) {
        case TargetPlatform.android:
        case TargetPlatform.fuchsia:
          return Icons.arrow_back;
        case TargetPlatform.iOS:
          return Icons.arrow_back_ios;
      }
      assert(false);
      return null;
    }

    final Orientation orientation = MediaQuery.of(context).orientation;
    return new Scaffold(
        key: _scaffoldKey,
        appBar: AppBar(
          leading: IconButton(
            icon: Icon(_backIcon()),
            alignment: Alignment.centerLeft,
            tooltip: 'Back',
            onPressed: () {
              Navigator.pop(context);
            },
          ),
          title: Text(toolbarname),
          backgroundColor: Colors.white,
        ),
        body: Container(
          child: Column(
            children: <Widget>[

              new Container(
                height: 50.0,
                alignment: Alignment.topLeft,
                margin: EdgeInsets.only(top: 7.0),
                child: new Row(
                  children: <Widget>[
                    _verticalD(),
                    new GestureDetector(
                      onTap: () {
                        /*Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => signup_screen()));*/
                      },
                      child: new Text(
                        'Contact Us',
                        style: TextStyle(
                            fontSize: 18.0,
                            color: Colors.black87,
                            fontWeight: FontWeight.bold),
                      ),
                    ),
                  ],
                ),
              ),
              Container(
                margin: EdgeInsets.only(left: 10.0),
                child: Card(
                    child: Container(
                      //  padding: EdgeInsets.only(left: 10.0,top: 15.0,bottom: 5.0,right: 5.0),

                      child: Column(
                        mainAxisSize: MainAxisSize.max,
                        mainAxisAlignment: MainAxisAlignment.spaceBetween,
                        children: <Widget>[
                          Container(
                              padding: EdgeInsets.only(
                                  left: 10.0, top: 15.0, bottom: 15.0),
                              child: GestureDetector(
                                child: Row(
                                  children: <Widget>[
                                    Icon(Icons.mail, color: Colors.black54),
                                    Container(
                                      margin: EdgeInsets.only(left: 5.0),
                                    ),
                                    Text(
                                      'Email US',
                                      style: TextStyle(
                                        fontSize: 17.0,
                                        color: Colors.black87,
                                      ),
                                    ),
                                  ],
                                ),
                                onTap: () {
                                  showDemoDialog<DialogDemoAction>(
                                      context: context,
                                      child: AlertDialog(
                                          title: const Text('Terms Use'),
                                          content: Text(
                                              "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
                                              style: dialogTextStyle),
                                          actions: <Widget>[
                                            FlatButton(
                                                child: const Text('DISAGREE'),
                                                onPressed: () {
                                                  Navigator.pop(context,
                                                      DialogDemoAction.disagree);
                                                }),
                                            /*  FlatButton(
                                            child: const Text('AGREE'),
                                            onPressed: () {
                                              Navigator.pop(context,
                                                  DialogDemoAction.agree);
                                            })*/
                                          ]));
                                },
                              )),
                          Divider(
                            height: 5.0,
                          ),
                          Container(
                              padding: EdgeInsets.only(
                                  left: 10.0, top: 15.0, bottom: 15.0),
                              child: GestureDetector(
                                  child: Row(
                                    children: <Widget>[
                                      Icon(Icons.info,
                                          color: Colors.black54),
                                      Container(
                                        margin: EdgeInsets.only(left: 5.0),
                                      ),
                                      Text(
                                        'About US',
                                        style: TextStyle(
                                            fontSize: 17.0, color: Colors.black87),
                                      ),
                                    ],
                                  ),
                                  onTap: () {
                                    showDemoDialog<DialogDemoAction>(
                                        context: context,
                                        child: AlertDialog(
                                            title: const Text('About Us'),
                                            content: Text(
                                                "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
                                                style: dialogTextStyle),
                                            actions: <Widget>[
                                              FlatButton(
                                                  child: const Text('DISAGREE'),
                                                  onPressed: () {
                                                    Navigator.pop(context,
                                                        DialogDemoAction.disagree);
                                                  }),
                                              /* FlatButton(
                                              child: const Text('AGREE'),
                                              onPressed: () {
                                                Navigator.pop(context,
                                                    DialogDemoAction.agree);
                                              })*/
                                            ]));
                                  })),
                          Divider(
                            height: 5.0,
                          ),
                          Container(
                              padding: EdgeInsets.only(
                                  left: 10.0, top: 15.0, bottom: 15.0),
                              child: GestureDetector(
                                  child: Row(
                                    children: <Widget>[
                                      Icon(Icons.feedback,
                                          color: Colors.black54),
                                      Container(
                                        margin: EdgeInsets.only(left: 5.0),
                                      ),
                                      Text(
                                        'Send Feedback',
                                        style: TextStyle(
                                            fontSize: 17.0, color: Colors.black87),
                                      ),
                                    ],
                                  ),
                                  onTap: () {
                                    showDemoDialog<DialogDemoAction>(
                                        context: context,
                                        child: AlertDialog(
                                            title: const Text('Send Feedback'),
                                            content: Text(
                                                "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
                                                style: dialogTextStyle),
                                            actions: <Widget>[
                                              FlatButton(
                                                  child: const Text('DISAGREE'),
                                                  onPressed: () {
                                                    Navigator.pop(context,
                                                        DialogDemoAction.disagree);
                                                  }),
                                              /* FlatButton(
                                              child: const Text('AGREE'),
                                              onPressed: () {
                                                Navigator.pop(context,
                                                    DialogDemoAction.agree);
                                              })*/
                                            ]));
                                  })),
                        ],
                      ),
                    )),
              )
            ],
          ),
        ));
  }

  void showDemoDialog<T>({BuildContext context, Widget child}) {
    showDialog<T>(
      context: context,
      builder: (BuildContext context) => child,
    ).then<void>((T value) {
      // The value passed to Navigator.pop() or null.
      if (value != null) {
        /*_scaffoldKey.currentState.showSnackBar(SnackBar(
            content: Text('You selected: $value')
        ));*/
      }
    });
  }

  _verticalD() => Container(
    margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
  );

  _verticalDivider() => Container(
    padding: EdgeInsets.all(2.0),
  );

  Widget _status(status) {
    if (status == 'Cabcel Order') {
      return FlatButton.icon(
          label: Text(
            status,
            style: TextStyle(color: Colors.red),
          ),
          icon: const Icon(
            Icons.highlight_off,
            size: 18.0,
            color: Colors.red,
          ),
          onPressed: () {
            // Perform some action
          });
    } else {
      return FlatButton.icon(
          label: Text(
            status,
            style: TextStyle(color: Colors.green),
          ),
          icon: const Icon(
            Icons.check_circle,
            size: 18.0,
            color: Colors.green,
          ),
          onPressed: () {
            // Perform some action
          });
    }
  }

  erticalD() => Container(
    margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
  );

  bool a = true;
  String mText = "Press to hide";
  double _lowerValue = 1.0;
  double _upperValue = 100.0;

  void _visibilitymethod() {
    setState(() {
      if (a) {
        a = false;
        mText = "Press to show";
      } else {
        a = true;
        mText = "Press to hide";
      }
    });
  }
}
import 'package:f_groceries/Cart_Screen.dart';
import 'package:f_groceries/checkout_screen.dart';
import 'package:flutter/material.dart';
import 'package:carousel_pro/carousel_pro.dart';

class Item_Details extends StatefulWidget {
  @override
  State<StatefulWidget> createState() => item_details();
}

class item_details extends State<Item_Details> {
  String toolbarname = 'Fruiys & Vegetables';
  final GlobalKey<ScaffoldState> _scaffoldKey = GlobalKey<ScaffoldState>();
  List list = ['12', '11'];

  String itemname = 'Apple';
  int item = 0;
  String itemprice= '\$15';


  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    final ThemeData theme = Theme.of(context);
    final TextStyle titleStyle =
    theme.textTheme.headline.copyWith(color: Colors.white);
    final TextStyle descriptionStyle = theme.textTheme.subhead;
    IconData _backIcon() {
      switch (Theme.of(context).platform) {
        case TargetPlatform.android:
        case TargetPlatform.fuchsia:
          return Icons.arrow_back;
        case TargetPlatform.iOS:
          return Icons.arrow_back_ios;
      }
      assert(false);
      return null;
    }

    IconData _add_icon() {
      switch (Theme.of(context).platform) {
        case TargetPlatform.android:
        case TargetPlatform.fuchsia:
          return Icons.add_circle;
        case TargetPlatform.iOS:
          return Icons.add_circle;
      }
      assert(false);
      return null;
    }
    IconData _sub_icon() {
      switch (Theme.of(context).platform) {
        case TargetPlatform.android:
        case TargetPlatform.fuchsia:
          return Icons.remove_circle;
        case TargetPlatform.iOS:
          return Icons.remove_circle;
      }
      assert(false);
      return null;
    }
    return new Scaffold(
        key: _scaffoldKey,
        appBar: AppBar(
          leading: IconButton(
            icon: Icon(_backIcon()),
            alignment: Alignment.centerLeft,
            tooltip: 'Back',
            onPressed: () {
              Navigator.pop(context);
            },
          ),
          title: Text(toolbarname),
          backgroundColor: Colors.white,
          actions: <Widget>[
            new Padding(
              padding: const EdgeInsets.all(10.0),
              child: new Container(
                height: 150.0,
                width: 30.0,
                child: new GestureDetector(
                  onTap: () {
                    /*Navigator.of(context).push(
                  new MaterialPageRoute(
                      builder:(BuildContext context) =>
                      new CartItemsScreen()
                  )
              );*/
                  },
                  child: Stack(
                    children: <Widget>[
                      new IconButton(
                          icon: new Icon(
                            Icons.shopping_cart,
                            color: Colors.black,
                          ),
                          onPressed: (){
                            Navigator.push(context, MaterialPageRoute(builder: (context) =>Checkout()));
                          }),
                      list.length == 0
                          ? new Container()
                          : new Positioned(
                              child: new Stack(
                              children: <Widget>[
                                new Icon(Icons.brightness_1,
                                    size: 20.0, color: Colors.orange.shade500),
                                new Positioned(
                                    top: 4.0,
                                    right: 5.5,
                                    child: new Center(
                                      child: new Text(
                                        list.length.toString(),
                                        style: new TextStyle(
                                            color: Colors.white,
                                            fontSize: 11.0,
                                            fontWeight: FontWeight.w500),
                                      ),
                                    )),
                              ],
                            )),
                    ],
                  ),
                ),
              ),
            )
          ],
        ),
        body: Container(
            padding: const EdgeInsets.all(8.0),

            child:SingleChildScrollView(

              child: Column(
              children: <Widget>[

             Card(
               elevation: 4.0,
              child:Container(
                color: Colors.white,
                child: Column(
                  crossAxisAlignment: CrossAxisAlignment.start,
                  children: <Widget>[
                    // photo and title
                    SizedBox(
                      height: 250.0,

                      child: Stack(
                        alignment: Alignment.center,

                        children: <Widget>[
                          new Container(
                            child: new Carousel(
                              images: [
                                new AssetImage(
                                  'images/apple.jpg',
                                  // package: destination.assetPackage,
                                ),
                                new AssetImage(
                                  'images/tomato.jpg',
                                  // package: destination.assetPackage,
                                ),
                                new AssetImage(
                                  'images/lemons.jpg',
                                  // package: destination.assetPackage,
                                ),
                                new AssetImage(
                                  'images/kiwi.jpg',
                                  // package: destination.assetPackage,
                                ),
                                new AssetImage(
                                  'images/guava.jpg',
                                  // package: destination.assetPackage,
                                ),
                                new AssetImage(
                                  'images/grapes.jpg',
                                  // package: destination.assetPackage,
                                ),
                              ],
                              boxFit: BoxFit.scaleDown,
                              showIndicator: false,

                              autoplay: false,
                            ),
                          )
                        ],
                      ),

                    ),
                  ]),
            ),
             ),

             Container(
               padding: const EdgeInsets.fromLTRB(16.0, 16.0, 16.0, 0.0),
               child: DefaultTextStyle(
                 style: descriptionStyle,
                 child: Row(
                     mainAxisSize: MainAxisSize.max,
                     mainAxisAlignment: MainAxisAlignment.spaceBetween,
                     children: <Widget>[
                 // three line description
                 Padding(
                 padding: const EdgeInsets.only(bottom: 8.0),
                 child: Text(
                 itemname,
                 style: descriptionStyle.copyWith(
                   fontSize: 20.0,
                 fontWeight: FontWeight.bold,
                 color: Colors.black87),
               ),
             ),
             Padding(
               padding: const EdgeInsets.only(bottom: 8.0),
               child: Text(
                 itemprice,
                 style: descriptionStyle.copyWith(
                   fontSize: 20.0,
                     color: Colors.black54),
               ),
             ),
              ],
            )
        )
             ),
                Container(
                  margin: EdgeInsets.all(10.0),
                  child: Card(
                      child: Container(
                          padding: const EdgeInsets.fromLTRB(10.0, 20.0, 10.0, 20.0),
                          child: DefaultTextStyle(
                              style: descriptionStyle,
                              child: Row(
                                mainAxisSize: MainAxisSize.max,
                                mainAxisAlignment: MainAxisAlignment.spaceBetween,
                                children: <Widget>[
                                  // three line description
                                  Row(
                                    children: <Widget>[
                                      new IconButton(
                                        icon: Icon(_add_icon(),color: Colors.amber.shade500),
                                        onPressed: () {

                                            item = item + 1;

                                        },
                                      ),
                                      Container(
                                        margin: EdgeInsets.only(left:2.0),
                                      ),
                                      Text(
                                        item.toString(),
                                        style: descriptionStyle.copyWith(
                                            fontSize: 20.0,
                                            color: Colors.black87),
                                      ),
                                      Container(
                                        margin: EdgeInsets.only(right:2.0),
                                      ),
                                      new IconButton(
                                        icon: Icon(_sub_icon(),color: Colors.amber.shade500),
                                        onPressed: () {
                                          if(item<0){

                                          }
                                          else{
                                            item = item -1;
                                          }
                                        },
                                      ),
                                    ],
                                  ),

                                  Padding(
                                    padding: const EdgeInsets.only(bottom: 8.0),
                                    child:  Container(
                                      alignment: Alignment.center,
                                      child: OutlineButton(
                                          borderSide: BorderSide(color: Colors.amber.shade500),
                                          child: const Text('Add'),
                                          textColor: Colors.amber.shade500,
                                          onPressed: () {
                                            Navigator.push(context, MaterialPageRoute(builder: (context)=> Cart_screen()));
                                          },
                                          shape: new OutlineInputBorder(
                                            borderRadius: BorderRadius.circular(30.0),
                                          )),
                                    ),
                                  ),
                                ],
                              )
                          )
                      )
                  )
                ),

             Container(
                 padding: const EdgeInsets.fromLTRB(16.0, 16.0, 16.0, 0.0),
                 child: DefaultTextStyle(
                     style: descriptionStyle,
                     child: Row(
                       mainAxisSize: MainAxisSize.max,
                       mainAxisAlignment: MainAxisAlignment.spaceBetween,
                       children: <Widget>[
                         // three line description
                         Padding(
                           padding: const EdgeInsets.only(bottom: 8.0),
                           child: Text(
                             'Details',
                             style: descriptionStyle.copyWith(
                                 fontSize: 20.0,
                                 fontWeight: FontWeight.bold,
                                 color: Colors.black87),
                           ),
                         ),
                       ],
                     )
                 )
             ),
             Container(
                 padding: const EdgeInsets.fromLTRB(20.0, 10.0, 10.0, 0.0),

                          child: Text("Grocery stores also offer non-perishable foods that are packaged in bottles, boxes, and cans; some also have bakeries, butchers, delis, and fresh produce. Large grocery stores that stock significant amounts of non-food products, such as clothing and household items, are called supermarkets. Some large supermarkets also include a pharmacy, and customer service, redemption, and electronics sections.",
                            maxLines: 10,
                            style: TextStyle(fontSize: 13.0,color: Colors.black38)
                          )
             ),

    ]
    )
    )
        )
    );
  }
}
import 'package:f_groceries/HomeScreen.dart';
import 'package:f_groceries/signup_screen.dart';
import 'package:flutter/material.dart';

class Login_Screen extends StatefulWidget {


  final Key fieldKey;
  final String hintText;
  final String labelText;
  final String helperText;
  final FormFieldSetter<String> onSaved;
  final FormFieldValidator<String> validator;
  final ValueChanged<String> onFieldSubmitted;

  const Login_Screen({Key key, this.fieldKey, this.hintText, this.labelText, this.helperText, this.onSaved, this.validator, this.onFieldSubmitted}) : super(key: key);

  ThemeData buildTheme() {
    final ThemeData base = ThemeData();
    return base.copyWith(
      hintColor: Colors.red,
      inputDecorationTheme: InputDecorationTheme(
        labelStyle: TextStyle(
            color: Colors.yellow,
            fontSize: 24.0
        ),
      ),
    );
  }
  @override
  State<StatefulWidget> createState() => login();
}

class login extends State<Login_Screen> {

  ShapeBorder shape;
  final scaffoldKey = GlobalKey<ScaffoldState>();
  final formKey = GlobalKey<FormState>();

  String _email;
  String _password;
  final GlobalKey<FormState> _formKey = GlobalKey<FormState>();

  bool _autovalidate = false;
  bool _formWasEdited = false;

  String _validateName(String value) {
    _formWasEdited = true;
    if (value.isEmpty)
      return 'Name is required.';
    final RegExp nameExp = RegExp(r'^[A-Za-z ]+$');
    if (!nameExp.hasMatch(value))
      return 'Please enter only alphabetical characters.';
    return null;
  }

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    bool _obscureText = true;
    return new Scaffold(
        key: scaffoldKey,
        appBar: new AppBar(
          title: Text('Login'),
          backgroundColor: Colors.white,
        ),
        body: SafeArea(
          child: new SingleChildScrollView(
            child: new Column(
              mainAxisSize: MainAxisSize.min,
              children: <Widget>[
                new Container(
                  height: 50.0,
                  alignment: Alignment.topLeft,
                  margin: EdgeInsets.only(top: 7.0),
                  child: new Row(
                    children: <Widget>[
                      _verticalD(),
                      new GestureDetector(
                        onTap: () {
                          /* Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => login_screen()));*/
                        },
                        child: new Text(
                          'Login',
                          style: TextStyle(
                              fontSize: 20.0,
                              color: Colors.black87,
                              fontWeight: FontWeight.bold),
                        ),
                      ),
                      _verticalD(),
                      new GestureDetector(
                        onTap: () {
                          Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => Signup_Screen()));
                        },
                        child: new Text(
                          'Signup',
                          style: TextStyle(
                              fontSize: 20.0,
                              color: Colors.black26,
                              fontWeight: FontWeight.bold),
                        ),
                      ),
                    ],
                  ),
                ),
                new SafeArea(

                    top: false,
                    bottom: false,
                    child: Card(
                        elevation: 5.0,
                        child: Form(
                            key: formKey,
                            autovalidate: _autovalidate,
                            child: SingleChildScrollView(
                              padding: const EdgeInsets.all(16.0),
                              child: Column(
                                  crossAxisAlignment: CrossAxisAlignment.stretch,
                                  children: <Widget>[
                                    const SizedBox(height: 24.0),
                                    TextFormField(
                                      decoration: const InputDecoration(
                                          border: UnderlineInputBorder(
                                            borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                          ),
                                          focusedBorder:  UnderlineInputBorder(
                                            borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                          ),
                                          icon: Icon(Icons.email,color: Colors.black38,),
                                          hintText: 'Your email address',
                                          labelText: 'E-mail',
                                          labelStyle: TextStyle(color: Colors.black54)
                                      ),
                                      keyboardType: TextInputType.emailAddress,
                                      validator: (val) =>
                                      !val.contains('@') ? 'Not a valid email.' : null,
                                      onSaved: (val) => _email = val,
                                    ),

                                    const SizedBox(height: 24.0),
                                    TextFormField(
                                      obscureText: true,
                                      decoration: const InputDecoration(
                                          border: UnderlineInputBorder(
                                            borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                          ),
                                          focusedBorder:  UnderlineInputBorder(
                                            borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                          ),
                                          icon: Icon(Icons.lock,color: Colors.black38,),
                                          hintText: 'Your password',
                                          labelText: 'Password',
                                          labelStyle: TextStyle(color: Colors.black54)
                                      ),

                                      validator: (val) =>
                                      val.length < 6 ? 'Password too short.' : null,
                                      onSaved: (val) => _password = val,
                                    ),

                                    SizedBox(height: 35.0,),
                                    new Container(
                                      child: Row(
                                        mainAxisSize: MainAxisSize.max,
                                        mainAxisAlignment: MainAxisAlignment.spaceBetween,
                                        children: <Widget>[

                                          new Container(
                                            alignment: Alignment.bottomLeft,
                                            margin: EdgeInsets.only(left: 10.0),
                                            child: new GestureDetector(
                                              onTap: (){

                                              },
                                              child: Text('FORGOT PASSWORD?',style: TextStyle(
                                                  color: Colors.blueAccent,fontSize: 13.0
                                              ),),
                                            ),
                                          ),
                                          new Container(
                                            alignment: Alignment.bottomRight,
                                            child: new GestureDetector(
                                              onTap: (){
                                                _submit();
                                              },
                                              child: Text('LOGIN',style: TextStyle(
                                                  color: Colors.orange,fontSize: 20.0,fontWeight: FontWeight.bold
                                              ),),
                                            ),
                                          ),
                                        ],
                                      ),
                                    ),

                                    /*   const SizedBox(height:24.0),
                            new Row(
                              crossAxisAlignment: CrossAxisAlignment.stretch,
                              children: <Widget>[
                                new GestureDetector(
                                  onTap: (){
                                  },
                                  child: Text('FORGOT PASSWORD?',style: TextStyle(
                                    color: Colors.blueAccent,fontSize: 13.0
                                  ),),
                                ),
                                new GestureDetector(
                                  onTap: (){
                                  },
                                  child: Text('LOGIN',style: TextStyle(
                                      color: Colors.orange,fontSize: 15.0
                                  ),),
                                ),
                              ],
                            )
*/
                                  ]
                              ),
                            )

                        )        //login,
                    ))
              ],
            ),
          )
        ));
  }

  void _submit() {
    final form = formKey.currentState;

    if (form.validate()) {
      form.save();

      // Email & password matched our validation rules
      // and are saved to _email and _password fields.
      _performLogin();
    }
    else{
      showInSnackBar('Please fix the errors in red before submitting.');

    }
  }

  void showInSnackBar(String value) {
    scaffoldKey.currentState.showSnackBar(SnackBar(
        content: Text(value)
    ));
  }
  void _performLogin() {
    // This is just a demo, so no actual login here.
    Navigator.push(context, MaterialPageRoute(builder: (context)=> Home_screen()));
  }

  _verticalD() => Container(
        margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
      );

  }
  import 'package:f_groceries/HomeScreen.dart';
import 'package:flutter/material.dart';
import 'dart:async';


void main() => runApp(new MyApp());

class MyApp extends StatelessWidget {
  // This widget is the root of your application.
  @override
  Widget build(BuildContext context) {
    return new MaterialApp(
        theme: new ThemeData(
          // This is the theme of your application.
          //
          // Try running your application with "flutter run". You'll see the
          // application has a blue toolbar. Then, without quitting the app, try
          // changing the primarySwatch below to Colors.green and then invoke
          // "hot reload" (press "r" in the console where you ran "flutter run",
          // or press Run > Flutter Hot Reload in IntelliJ). Notice that the
          // counter didn't reset back to zero; the application is not restarted.

            primaryColor: Colors.white,
            primaryColorDark: Colors.white30,
            accentColor: Colors.blue

        ),
      home: new MyHomePage(title: 'Groceries'),
    );
  }
}

class MyHomePage extends StatefulWidget {
  MyHomePage({Key key, this.title}) : super(key: key);

  // This widget is the home page of your application. It is stateful, meaning
  // that it has a State object (defined below) that contains fields that affect
  // how it looks.

  // This class is the configuration for the state. It holds the values (in this
  // case the title) provided by the parent (in this case the App widget) and
  // used by the build method of the State. Fields in a Widget subclass are
  // always marked "final".

  final String title;

  @override
  _MyHomePageState createState() => new _MyHomePageState();
}

class _MyHomePageState extends State<MyHomePage> {

  startTime() async {
    var _duration = new Duration(seconds: 3);
    return new Timer(_duration, navigationPage);
  }

  void navigationPage() {
    Navigator.push(context, MaterialPageRoute(builder: (context) => Home_screen()));

  }

  @override
  void initState() {
    super.initState();
    startTime();
  }
  @override
  Widget build(BuildContext context) {
    // TODO: implement build

    return new Container(
      alignment: Alignment.center,
      decoration: new BoxDecoration(color: Colors.white),
      child: new Container(
        color: Colors.black12,
        margin: new EdgeInsets.all(30.0),
        width: 250.0,
        height: 250.0,
        child: new Image.asset(
          'images/gro.jpg',
        ),
      ),
    );
  }

}

class address {

  final int status;
  final String message;
  final List<Data> data;

  address({this.status,this.message,this.data});

  factory address.fromJson(Map<String, dynamic> parsedJson){

    var list = parsedJson['images'] as List;
    print(list.runtimeType);
    List<Data> dataList = list.map((i) => Data.fromJson(i)).toList();


    return address(
        status: parsedJson['status'],
        message: parsedJson['message'],
        data: dataList

    );
  }

}

class Data {

  final int id ;
  final String name;
  final String mobilenumber;
  final String address;
  final String city;
  final String distric;
  final String state;
  final String pincode;

  Data({this.id, this.name, this.mobilenumber, this.address, this.city,
      this.distric, this.state, this.pincode});

  factory Data.fromJson(Map<String,dynamic> parsedJson){
    return Data(
      id: parsedJson['id'],
      name: parsedJson['name'],
      mobilenumber: parsedJson['mobilenumber'],
      address: parsedJson['address'],
      city: parsedJson['city'],
      distric: parsedJson['distric'],
        state: parsedJson['state'],
        pincode: parsedJson['pincode']
    );
  }


}
import 'package:f_groceries/Cart_Screen.dart';
import 'package:f_groceries/item_details.dart';
import 'package:flutter/material.dart';
import 'package:flutter_range_slider/flutter_range_slider.dart';

class Oder_History extends StatefulWidget {
  final String toolbarname;

  Oder_History({Key key, this.toolbarname}) : super(key: key);

  @override
  State<StatefulWidget> createState() => oder_history(toolbarname);
}

class Item {
  final String name;
  final String deliveryTime;
  final String oderId;
  final String oderAmount;
  final String paymentType;
  final String address;
  final String cancelOder;

  Item(
      {this.name,
      this.deliveryTime,
      this.oderId,
      this.oderAmount,
      this.paymentType,
      this.address,
      this.cancelOder});
}

class oder_history extends State<Oder_History> {
  List list = ['12', '11'];
  bool checkboxValueA = true;
  bool checkboxValueB = false;
  bool checkboxValueC = false;
  VoidCallback _showBottomSheetCallback;
  List<Item> itemList = <Item>[
    Item(
        name: 'Jhone Miller',
        deliveryTime: '26-5-2106',
        oderId: '#CN23656',
        oderAmount: '\₹ 650',
        paymentType: 'online',
        address: '1338 Karen Lane,Louisville,Kentucky',
        cancelOder: 'Cancel Order'),
    Item(
        name: 'Gautam Dass',
        deliveryTime: '10-8-2106',
        oderId: '#CN33568',
        oderAmount: '\₹ 900',
        paymentType: 'COD',
        address: '319 Alexander Drive,Ponder,Texas',
        cancelOder: 'View Receipt'),
    Item(
        name: 'Jhone Hill',
        deliveryTime: '23-3-2107',
        oderId: '#CN75695',
        oderAmount: '\₹ 250',
        paymentType: 'online',
        address: '92 Jarvis Street,Buffalo,New York',
        cancelOder: 'View Receipt'),
    Item(
        name: 'Miller Root',
        deliveryTime: '10-5-2107',
        oderId: '#CN45238',
        oderAmount: '\₹ 500',
        paymentType: 'Bhim/upi',
        address: '103 Romrog Way,Grand Island,Nebraska',
        cancelOder: 'Cancel Order'),
    Item(
        name: 'Lag Gilli',
        deliveryTime: '26-10-2107',
        oderId: '#CN69532',
        oderAmount: '\₹ 1120',
        paymentType: 'online',
        address: '8 Clarksburg Park,Marble Canyon,Arizona',
        cancelOder: 'View Receipt'),
  ];

  // String toolbarname = 'Fruiys & Vegetables';
  final GlobalKey<ScaffoldState> _scaffoldKey = GlobalKey<ScaffoldState>();
  String toolbarname;

  oder_history(this.toolbarname);

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    IconData _backIcon() {
      switch (Theme.of(context).platform) {
        case TargetPlatform.android:
        case TargetPlatform.fuchsia:
          return Icons.arrow_back;
        case TargetPlatform.iOS:
          return Icons.arrow_back_ios;
      }
      assert(false);
      return null;
    }

    var size = MediaQuery.of(context).size;

    /*24 is for notification bar on Android*/
    final double itemHeight = (size.height - kToolbarHeight - 24) / 2;
    final double itemWidth = size.width / 2;

    final Orientation orientation = MediaQuery.of(context).orientation;
    return new Scaffold(
        key: _scaffoldKey,
        appBar: AppBar(
          leading: IconButton(
            icon: Icon(_backIcon()),
            alignment: Alignment.centerLeft,
            tooltip: 'Back',
            onPressed: () {
              Navigator.pop(context);
            },
          ),
          title: Text(toolbarname),
          backgroundColor: Colors.white,
        ),
        body: ListView.builder(
            itemCount: itemList.length,
            itemBuilder: (BuildContext cont, int ind) {
              return SafeArea(
                  child: Column(children: <Widget>[
                Container(
                    margin: EdgeInsets.only(left: 5.0, right: 5.0, bottom: 5.0),
                    color:Colors.black12,
                    child: Card(
                        elevation: 4.0,
                        child: Container(
                            padding: const EdgeInsets.fromLTRB(
                                10.0, 10.0, 10.0, 10.0),
                            child: GestureDetector(
                                child: Column(
                              mainAxisSize: MainAxisSize.max,
                              mainAxisAlignment: MainAxisAlignment.start,
                              children: <Widget>[
                                // three line description
                                Container(
                                  alignment: Alignment.topLeft,
                                  child: Text(
                                    itemList[ind].name,
                                    style: TextStyle(
                                      fontSize: 16.0,
                                      fontStyle: FontStyle.normal,
                                      color: Colors.black87,
                                    ),
                                  ),
                                ),

                                Container(
                                  margin: EdgeInsets.only(top: 3.0),
                                ),
                                Container(
                                  alignment: Alignment.topLeft,
                                  child: Text(
                                    'To Deliver On :' +
                                        itemList[ind].deliveryTime,
                                    style: TextStyle(
                                        fontSize: 13.0, color: Colors.black54),
                                  ),
                                ),
                                Divider(
                                  height: 10.0,
                                  color: Colors.amber.shade500,
                                ),

                                Row(
                                  mainAxisSize: MainAxisSize.max,
                                  mainAxisAlignment:
                                      MainAxisAlignment.spaceBetween,
                                  children: <Widget>[
                                    Container(
                                        padding: EdgeInsets.all(3.0),
                                        child: Column(
                                          mainAxisAlignment:
                                              MainAxisAlignment.center,
                                          children: <Widget>[
                                            Text(
                                              'Order Id',
                                              style: TextStyle(
                                                  fontSize: 13.0,
                                                  color: Colors.black54),
                                            ),
                                            Container(
                                              margin: EdgeInsets.only(top: 3.0),
                                              child: Text(
                                                itemList[ind].oderId,
                                                style: TextStyle(
                                                    fontSize: 15.0,
                                                    color: Colors.black87),
                                              ),
                                            )
                                          ],
                                        )),
                                    Container(
                                        padding: EdgeInsets.all(3.0),
                                        child: Column(
                                          mainAxisAlignment:
                                              MainAxisAlignment.center,
                                          children: <Widget>[
                                            Text(
                                              'Order Amount',
                                              style: TextStyle(
                                                  fontSize: 13.0,
                                                  color: Colors.black54),
                                            ),
                                            Container(
                                              margin: EdgeInsets.only(top: 3.0),
                                              child: Text(
                                                itemList[ind].oderAmount,
                                                style: TextStyle(
                                                    fontSize: 15.0,
                                                    color: Colors.black87),
                                              ),
                                            ),
                                          ],
                                        )),
                                    Container(
                                        padding: EdgeInsets.all(3.0),
                                        child: Column(
                                          mainAxisAlignment:
                                              MainAxisAlignment.center,
                                          children: <Widget>[
                                            Text(
                                              'Payment Type',
                                              style: TextStyle(
                                                  fontSize: 13.0,
                                                  color: Colors.black54),
                                            ),
                                            Container(
                                              margin: EdgeInsets.only(top: 3.0),
                                              child: Text(
                                                itemList[ind].paymentType,
                                                style: TextStyle(
                                                    fontSize: 15.0,
                                                    color: Colors.black87),
                                              ),
                                            )
                                          ],
                                        )),
                                  ],
                                ),
                                Divider(
                                  height: 10.0,
                                  color: Colors.amber.shade500,
                                ),

                                Row(
                                  mainAxisAlignment: MainAxisAlignment.start,
                                  children: <Widget>[
                                    Icon(
                                      Icons.location_on,
                                      size: 20.0,
                                        color: Colors.amber.shade500,
                                    ),
                                    Text(itemList[ind].address,
                                        style: TextStyle(
                                            fontSize: 13.0,
                                            color: Colors.black54)),
                                  ],
                                ),
                                Divider(
                                  height: 10.0,
                                  color: Colors.amber.shade500,
                                ),
                                Container(
                                 child:_status(itemList[ind].cancelOder)
                                )
                              ],
                            ))))),
              ]));
            }));
  }

  _verticalDivider() => Container(
        padding: EdgeInsets.all(2.0),
      );

  Widget _status(status) {
    if(status == 'Cancel Order'){
     return FlatButton.icon(
          label: Text(status,style: TextStyle(color: Colors.red),),
          icon: const Icon(Icons.highlight_off, size: 18.0,color: Colors.red,),
          onPressed: () {
            // Perform some action
          }
      );
    }
    else{
     return FlatButton.icon(
          label: Text(status,style: TextStyle(color: Colors.green),),
          icon: const Icon(Icons.check_circle, size: 18.0,color: Colors.green,),
          onPressed: () {
            // Perform some action
          }
      );
    }
    if (status == "3") {
      return Text('Process');
    } else if (status == "1") {
      return Text('Order');
    } else {
      return Text("Waiting");
    }
  }
 erticalD() => Container(
        margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
      );

  bool a = true;
  String mText = "Press to hide";
  double _lowerValue = 1.0;
  double _upperValue = 100.0;

  void _visibilitymethod() {
    setState(() {
      if (a) {
        a = false;
        mText = "Press to show";
      } else {
        a = true;
        mText = "Press to hide";
      }
    });
  }
}
import 'dart:async' show Future;
import 'package:flutter/services.dart' show rootBundle;
import 'dart:convert';
import 'package:f_groceries/model/Address_model.dart';

Future<String> _loadProduct() async{
  return await rootBundle.loadString('assets/address.json');
}

Future loadAddress() async{

  String jsonAddress = await _loadProduct();
  final jsonResponce = json.decode(jsonAddress);
  address address_model = new address.fromJson(jsonResponce);

} 
import 'package:f_groceries/Cart_Screen.dart';
import 'package:f_groceries/item_details.dart';
import 'package:flutter/material.dart';
import 'package:flutter_range_slider/flutter_range_slider.dart';

class Setting_Screen extends StatefulWidget {
  final String toolbarname;

  Setting_Screen({Key key, this.toolbarname}) : super(key: key);

  @override
  State<StatefulWidget> createState() => Setting(toolbarname);
}

class Setting extends State<Setting_Screen> {
  List list = ['12', '11'];

  bool switchValue = false;

  // String toolbarname = 'Fruiys & Vegetables';
  final GlobalKey<ScaffoldState> _scaffoldKey = GlobalKey<ScaffoldState>();
  String toolbarname;

  Setting(this.toolbarname);

  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    final ThemeData theme = Theme.of(context);
    final TextStyle dialogTextStyle =
        theme.textTheme.subhead.copyWith(color: theme.textTheme.caption.color);

    IconData _backIcon() {
      switch (Theme.of(context).platform) {
        case TargetPlatform.android:
        case TargetPlatform.fuchsia:
          return Icons.arrow_back;
        case TargetPlatform.iOS:
          return Icons.arrow_back_ios;
      }
      assert(false);
      return null;
    }

    final Orientation orientation = MediaQuery.of(context).orientation;
    return new Scaffold(
        key: _scaffoldKey,
        appBar: AppBar(
          leading: IconButton(
            icon: Icon(_backIcon()),
            alignment: Alignment.centerLeft,
            tooltip: 'Back',
            onPressed: () {
              Navigator.pop(context);
            },
          ),
          title: Text(toolbarname),
          backgroundColor: Colors.white,
        ),
        body: Container(
          child: Column(
            children: <Widget>[
              new Container(
                height: 50.0,
                alignment: Alignment.topLeft,
                margin: EdgeInsets.only(top: 7.0),
                child: new Row(
                  children: <Widget>[
                    _verticalD(),
                    new GestureDetector(
                      onTap: () {
                        /*Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => signup_screen()));*/
                      },
                      child: new Text(
                        'Notification',
                        style: TextStyle(
                            fontSize: 18.0,
                            color: Colors.black87,
                            fontWeight: FontWeight.bold),
                      ),
                    ),
                  ],
                ),
              ),
              Container(
                margin: EdgeInsets.only(left: 10.0),
                child: Card(
                    child: Container(
                  padding: EdgeInsets.only(
                      left: 10.0, top: 5.0, bottom: 5.0, right: 5.0),
                  child: Row(
                    mainAxisSize: MainAxisSize.max,
                    mainAxisAlignment: MainAxisAlignment.spaceBetween,
                    children: <Widget>[
                      Row(
                        children: <Widget>[
                          Icon(Icons.notifications, color: Colors.black54),
                          Container(
                            margin: EdgeInsets.only(left: 5.0),
                          ),
                          Text(
                            'Notification',
                            style: TextStyle(
                              fontSize: 17.0,
                              color: Colors.black87,
                            ),
                          ),
                        ],
                      ),
                      Switch(
                          value: switchValue,
                          onChanged: (bool value) {
                            setState(() {
                              switchValue = value;
                            });
                          }),
                    ],
                  ),
                )),
              ),
              Container(
                margin: EdgeInsets.only(top: 15.0),
              ),
              new Container(
                height: 50.0,
                alignment: Alignment.topLeft,
                margin: EdgeInsets.only(top: 7.0),
                child: new Row(
                  children: <Widget>[
                    _verticalD(),
                    new GestureDetector(
                      onTap: () {
                        /*Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => signup_screen()));*/
                      },
                      child: new Text(
                        'Legal',
                        style: TextStyle(
                            fontSize: 18.0,
                            color: Colors.black87,
                            fontWeight: FontWeight.bold),
                      ),
                    ),
                  ],
                ),
              ),
              Container(
                margin: EdgeInsets.only(left: 10.0),
                child: Card(
                    child: Container(
                  //  padding: EdgeInsets.only(left: 10.0,top: 15.0,bottom: 5.0,right: 5.0),

                  child: Column(
                    mainAxisSize: MainAxisSize.max,
                    mainAxisAlignment: MainAxisAlignment.spaceBetween,
                    children: <Widget>[
                      Container(
                          padding: EdgeInsets.only(
                              left: 10.0, top: 15.0, bottom: 15.0),
                          child: GestureDetector(
                            child: Row(
                              children: <Widget>[
                                Icon(Icons.assignment, color: Colors.black54),
                                Container(
                                  margin: EdgeInsets.only(left: 5.0),
                                ),
                                Text(
                                  'Terms Off Use',
                                  style: TextStyle(
                                    fontSize: 17.0,
                                    color: Colors.black87,
                                  ),
                                ),
                              ],
                            ),
                            onTap: () {
                              showDemoDialog<DialogDemoAction>(
                                  context: context,
                                  child: AlertDialog(
                                      title: const Text('Terms Use'),
                                      content: Text(
                                          "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
                                          style: dialogTextStyle),
                                      actions: <Widget>[
                                        FlatButton(
                                            child: const Text('DISAGREE'),
                                            onPressed: () {
                                              Navigator.pop(context,
                                                  DialogDemoAction.disagree);
                                            }),
                                      /*  FlatButton(
                                            child: const Text('AGREE'),
                                            onPressed: () {
                                              Navigator.pop(context,
                                                  DialogDemoAction.agree);
                                            })*/
                                      ]));
                            },
                          )),
                      Divider(
                        height: 5.0,
                      ),
                      Container(
                          padding: EdgeInsets.only(
                              left: 10.0, top: 15.0, bottom: 15.0),
                          child: GestureDetector(
                              child: Row(
                                children: <Widget>[
                                  Icon(Icons.lock_outline,
                                      color: Colors.black54),
                                  Container(
                                    margin: EdgeInsets.only(left: 5.0),
                                  ),
                                  Text(
                                    'Privacy Policy',
                                    style: TextStyle(
                                        fontSize: 17.0, color: Colors.black87),
                                  ),
                                ],
                              ),
                              onTap: () {
                                showDemoDialog<DialogDemoAction>(
                                    context: context,
                                    child: AlertDialog(
                                        title: const Text('About Us'),
                                        content: Text(
                                            "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book.",
                                            style: dialogTextStyle),
                                        actions: <Widget>[
                                          FlatButton(
                                              child: const Text('DISAGREE'),
                                              onPressed: () {
                                                Navigator.pop(context,
                                                    DialogDemoAction.disagree);
                                              }),
                                         /* FlatButton(
                                              child: const Text('AGREE'),
                                              onPressed: () {
                                                Navigator.pop(context,
                                                    DialogDemoAction.agree);
                                              })*/
                                        ]));
                              })),
                    ],
                  ),
                )),
              )
            ],
          ),
        ));
  }

  void showDemoDialog<T>({BuildContext context, Widget child}) {
    showDialog<T>(
      context: context,
      builder: (BuildContext context) => child,
    ).then<void>((T value) {
      // The value passed to Navigator.pop() or null.
      if (value != null) {
        /*_scaffoldKey.currentState.showSnackBar(SnackBar(
            content: Text('You selected: $value')
        ));*/
      }
    });
  }

  _verticalD() => Container(
        margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
      );

  _verticalDivider() => Container(
        padding: EdgeInsets.all(2.0),
      );

  Widget _status(status) {
    if (status == 'Cabcel Order') {
      return FlatButton.icon(
          label: Text(
            status,
            style: TextStyle(color: Colors.red),
          ),
          icon: const Icon(
            Icons.highlight_off,
            size: 18.0,
            color: Colors.red,
          ),
          onPressed: () {
            // Perform some action
          });
    } else {
      return FlatButton.icon(
          label: Text(
            status,
            style: TextStyle(color: Colors.green),
          ),
          icon: const Icon(
            Icons.check_circle,
            size: 18.0,
            color: Colors.green,
          ),
          onPressed: () {
            // Perform some action
          });
    }
  }

  erticalD() => Container(
        margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
      );

  bool a = true;
  String mText = "Press to hide";
  double _lowerValue = 1.0;
  double _upperValue = 100.0;

  void _visibilitymethod() {
    setState(() {
      if (a) {
        a = false;
        mText = "Press to show";
      } else {
        a = true;
        mText = "Press to hide";
      }
    });
  }
}
import 'package:f_groceries/logind_signup.dart';
import 'package:flutter/material.dart';

class Signup_Screen extends StatefulWidget {


  final Key fieldKey;
  final String hintText;
  final String labelText;
  final String helperText;
  final FormFieldSetter<String> onSaved;
  final FormFieldValidator<String> validator;
  final ValueChanged<String> onFieldSubmitted;

  const Signup_Screen({Key key, this.fieldKey, this.hintText, this.labelText, this.helperText, this.onSaved, this.validator, this.onFieldSubmitted}) : super(key: key);

  ThemeData buildTheme() {
    final ThemeData base = ThemeData();
    return base.copyWith(
      hintColor: Colors.red,
      inputDecorationTheme: InputDecorationTheme(
        labelStyle: TextStyle(
            color: Colors.yellow,
            fontSize: 24.0
        ),
      ),
    );
  }
  @override
  State<StatefulWidget> createState() => signup();
}

class signup extends State<Signup_Screen> {

  ShapeBorder shape;
  final scaffoldKey = GlobalKey<ScaffoldState>();
  final formKey = GlobalKey<FormState>();

  String _email;
  String _password;
  String _firstname;
  String _lastname;
  String _phone;
  final GlobalKey<FormState> _formKey = GlobalKey<FormState>();

  bool _autovalidate = false;
  bool _formWasEdited = false;


  @override
  Widget build(BuildContext context) {
    // TODO: implement build
    bool _obscureText = true;
    return new Scaffold(
        key: scaffoldKey,
        appBar: new AppBar(
          title: Text('Signup'),
          backgroundColor: Colors.white,
        ),
        body: SafeArea(
            child: new SingleChildScrollView(
              child: new Column(
                mainAxisSize: MainAxisSize.min,
                children: <Widget>[
                  new Container(
                    height: 50.0,
                    alignment: Alignment.topLeft,
                    margin: EdgeInsets.only(top: 7.0),
                    child: new Row(
                      children: <Widget>[
                        _verticalD(),
                        new GestureDetector(
                          onTap: () {
                             Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => Login_Screen()));
                          },
                          child: new Text(
                            'Login',
                            style: TextStyle(
                                fontSize: 20.0,
                                color: Colors.black26,
                                fontWeight: FontWeight.bold),
                          ),
                        ),
                        _verticalD(),
                        new GestureDetector(
                          onTap: () {
                            /*Navigator.push(
                            context,
                            MaterialPageRoute(
                                builder: (context) => signup_screen()));*/
                          },
                          child: new Text(
                            'Signup',
                            style: TextStyle(
                                fontSize: 20.0,
                                color: Colors.black87,
                                fontWeight: FontWeight.bold),
                          ),
                        ),
                      ],
                    ),
                  ),
                  new SafeArea(

                      top: false,
                      bottom: false,
                      child: Card(
                          elevation: 5.0,
                          child: Form(
                              key: formKey,
                              autovalidate: _autovalidate,
                              child: SingleChildScrollView(
                                padding: const EdgeInsets.all(16.0),
                                child: Column(
                                    crossAxisAlignment: CrossAxisAlignment.stretch,
                                    children: <Widget>[

                                      const SizedBox(height: 24.0),
                                      TextFormField(
                                        decoration: const InputDecoration(
                                            border: UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            focusedBorder:  UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            icon: Icon(Icons.person,color: Colors.black38,),
                                            hintText: 'Enter first name',
                                            labelText: 'First Name',
                                            labelStyle: TextStyle(color: Colors.black54)
                                        ),
                                        keyboardType: TextInputType.text,
                                        validator: (val) =>
                                        val.length < 1 ? 'Enter first name' : null,
                                        onSaved: (val) => _firstname = val,
                                      ),
                                      const SizedBox(height: 24.0),
                                      TextFormField(
                                        decoration: const InputDecoration(
                                            border: UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            focusedBorder:  UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            icon: Icon(Icons.perm_identity,color: Colors.black38,),
                                            hintText: 'Enter last name',
                                            labelText: 'Last Name',
                                            labelStyle: TextStyle(color: Colors.black54)
                                        ),
                                        keyboardType: TextInputType.text,
                                        validator: (val) =>
                                        val.length < 1 ? 'Enter last name' : null,
                                        onSaved: (val) => _lastname = val,
                                      ),
                                      const SizedBox(height: 24.0),
                                      TextFormField(
                                        decoration: const InputDecoration(
                                            border: UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            focusedBorder:  UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            icon: Icon(Icons.email,color: Colors.black38,),
                                            hintText: 'Your email address',
                                            labelText: 'E-mail',
                                            labelStyle: TextStyle(color: Colors.black54)
                                        ),
                                        keyboardType: TextInputType.emailAddress,
                                        validator: validateEmail,
                                        onSaved: (String val) {
                                          _email = val;
                                        },
                                      ),

                                      const SizedBox(height: 24.0),
                                      TextFormField(
                                        decoration: const InputDecoration(
                                            border: UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            focusedBorder:  UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            icon: Icon(Icons.phone_android,color: Colors.black38,),
                                            hintText: 'Your phone number',
                                            labelText: 'Phone',
                                            labelStyle: TextStyle(color: Colors.black54)
                                        ),
                                        keyboardType: TextInputType.phone,
                                        validator: validateMobile,
                                        onSaved: (String val) {
                                          _phone = val;
                                        },
                                      ),
                                      const SizedBox(height: 24.0),
                                      TextFormField(
                                        obscureText: true,
                                        decoration: const InputDecoration(
                                            border: UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            focusedBorder:  UnderlineInputBorder(
                                              borderSide: BorderSide(color: Colors.black87,style: BorderStyle.solid),
                                            ),
                                            icon: Icon(Icons.lock,color: Colors.black38,),
                                            hintText: 'Your password',
                                            labelText: 'Password',
                                            labelStyle: TextStyle(color: Colors.black54)
                                        ),

                                        validator: (val) =>
                                        val.length < 6 ? 'Password too short.' : null,
                                        onSaved: (val) => _password = val,
                                      ),

                                      SizedBox(height: 35.0,),
                                      new Container(
                                        child: Row(
                                          mainAxisSize: MainAxisSize.max,
                                          mainAxisAlignment: MainAxisAlignment.end,
                                          children: <Widget>[

                                            new Container(
                                              alignment: Alignment.bottomRight,
                                              child: new GestureDetector(
                                                onTap: (){
                                                  _submit();
                                                },
                                                child: Text('SIGNUP',style: TextStyle(
                                                    color: Colors.orange,fontSize: 20.0,fontWeight: FontWeight.bold
                                                ),),
                                              ),
                                            ),
                                          ],
                                        ),
                                      ),

                                      /*   const SizedBox(height:24.0),
                            new Row(
                              crossAxisAlignment: CrossAxisAlignment.stretch,
                              children: <Widget>[
                                new GestureDetector(
                                  onTap: (){
                                  },
                                  child: Text('FORGOT PASSWORD?',style: TextStyle(
                                    color: Colors.blueAccent,fontSize: 13.0
                                  ),),
                                ),
                                new GestureDetector(
                                  onTap: (){
                                  },
                                  child: Text('LOGIN',style: TextStyle(
                                      color: Colors.orange,fontSize: 15.0
                                  ),),
                                ),
                              ],
                            )
*/
                                    ]
                                ),
                              )

                          )        //login,
                      ))
                ],
              ),
            )
        ));
  }

  String validateEmail(String value) {
    Pattern pattern =
        r'^(([^<>()[\]\\.,;:\s@\"]+(\.[^<>()[\]\\.,;:\s@\"]+)*)|(\".+\"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$';
    RegExp regex = new RegExp(pattern);
    if (!regex.hasMatch(value))
      return 'Enter Valid Email';
    else
      return null;
  }

  String validateMobile(String value) {
// Indian Mobile number are of 10 digit only
    if (value.length != 10)
      return 'Mobile Number must be of 10 digit';
    else
      return null;
  }
  void _submit() {
    final form = formKey.currentState;

    if (form.validate()) {
      form.save();

      // Email & password matched our validation rules
      // and are saved to _email and _password fields.
      _performLogin();
    }
    else{
      showInSnackBar('Please fix the errors in red before submitting.');

    }
  }

  void showInSnackBar(String value) {
    scaffoldKey.currentState.showSnackBar(SnackBar(
        content: Text(value)
    ));
  }
  void _performLogin() {
    // This is just a demo, so no actual login here.
   /* final snackbar = SnackBar(
      content: Text('Email: $_email, password: $_password'),
    );
    scaffoldKey.currentState.showSnackBar(snackbar);*/
   Navigator.push(context, MaterialPageRoute(builder: (context)=> Login_Screen()));
  }

  _verticalD() => Container(
    margin: EdgeInsets.only(left: 10.0, right: 0.0, top: 0.0, bottom: 0.0),
  );

}
name: f_groceries
description: A new Flutter application.

# The following defines the version and build number for your application.
# A version number is three numbers separated by dots, like 1.2.43
# followed by an optional build number separated by a +.
# Both the version and the builder number may be overridden in flutter
# build by specifying --build-name and --build-number, respectively.
# Read more about versioning at semver.org.
version: 1.0.0+1

environment:
  sdk: ">=2.0.0-dev.68.0 <3.0.0"

dependencies:
  flutter:
    sdk: flutter


  # The following adds the Cupertino Icons font to your application.
  # Use with the CupertinoIcons class for iOS style icons.
  loader_search_bar: ^1.0.2
  cupertino_icons: ^0.1.2
  flutter_range_slider: "^1.0.1"
  carousel_pro: ^0.0.13

dev_dependencies:
  flutter_test:
    sdk: flutter


# For information on the generic Dart part of this file, see the
# following page: https://www.dartlang.org/tools/pub/pubspec

# The following section is specific to Flutter.
flutter:

  # The following line ensures that the Material Icons font is
  # included with your application, so that you can use the icons in
  # the material Icons class.
  uses-material-design: true
  assets:
     - images/back.jpg
     - images/groceries.jpg
     - images/grtwo.jpg
     - images/grthre.jpg
     - images/veg.jpg
     - images/frozen.jpg
     - images/bev.jpg
     - images/brand_f.jpg
     - images/be.jpg
     - images/eggs.jpg
     - images/home.jpg
     - images/nonveg.jpg
     - images/apple.jpg
     - images/grapes.jpg
     - images/guava.jpg
     - images/kiwi.jpg
     - images/lemons.jpg
     - images/pineapple.jpg
     - images/tomato.jpg
     - images/gro.jpg






     - assets/address.json




  # To add assets to your application, add an assets section, like this:
  # assets:
  #  - images/a_dot_burr.jpeg
  #  - images/a_dot_ham.jpeg

  # An image asset can refer to one or more resolution-specific "variants", see
  # https://flutter.io/assets-and-images/#resolution-aware.

  # For details regarding adding assets from package dependencies, see
  # https://flutter.io/assets-and-images/#from-packages

  # To add custom fonts to your application, add a fonts section here,
  # in this "flutter" section. Each entry in this list should have a
  # "family" key with the font family name, and a "fonts" key with a
  # list giving the asset and other descriptors for the font. For
  # example:
  # fonts:
  #   - family: Schyler
  #     fonts:
  #       - asset: fonts/Schyler-Regular.ttf
  #       - asset: fonts/Schyler-Italic.ttf
  #         style: italic
  #   - family: Trajan Pro
  #     fonts:
  #       - asset: fonts/TrajanPro.ttf
  #       - asset: fonts/TrajanPro_Bold.ttf
  #         weight: 700
  #
  # For details regarding fonts from package dependencies,
  # see https://flutter.io/custom-fonts/#from-packages
  import 'package:flutter/material.dart';
import 'package:flutter_test/flutter_test.dart';

import 'package:f_groceries/main.dart';

void main() {
  testWidgets('Counter increments smoke test', (WidgetTester tester) async {
    // Build our app and trigger a frame.
    await tester.pumpWidget(new MyApp());

    // Verify that our counter starts at 0.
    expect(find.text('0'), findsOneWidget);
    expect(find.text('1'), findsNothing);

    // Tap the '+' icon and trigger a frame.
    await tester.tap(find.byIcon(Icons.add));
    await tester.pump();

    // Verify that our counter has incremented.
    expect(find.text('0'), findsNothing);
    expect(find.text('1'), findsOneWidget);
  });
}
