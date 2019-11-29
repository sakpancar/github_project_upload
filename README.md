# create SSH connection
$ ssh-keygen



# github_project_upload
$ cd folder_which_you_want_to_upload

$ git init

$ git add .

$ git commit -m "upload my folder"

$ git remote rm origin - (When there is a problem)

$ git remote add origin https://github.com/sakpancar/syt_m100_imu_to_frame.git

$ git config --global --unset http.proxy  - (When there is a problem)

$ git config --global --unset https.proxy - (When there is a problem)

$ git push -u origin master
