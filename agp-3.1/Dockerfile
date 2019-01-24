FROM gradle:4.4

ENV ANDROID_HOME="/usr/local/android-sdk"

USER root

RUN mkdir $ANDROID_HOME
RUN chown gradle $ANDROID_HOME

USER gradle

RUN curl -o sdk-tools.zip "https://dl.google.com/android/repository/sdk-tools-linux-4333796.zip"
RUN unzip -q sdk-tools.zip -d $ANDROID_HOME
RUN rm sdk-tools.zip

WORKDIR $ANDROID_HOME/tools/bin
RUN yes | ./sdkmanager --licenses
RUN ./sdkmanager --update
RUN ./sdkmanager "platform-tools" "platforms;android-27" "build-tools;27.0.3"
