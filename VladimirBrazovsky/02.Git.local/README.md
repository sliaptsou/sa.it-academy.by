   # 02.Git.local
   48.  mkdir local_rep
   49.  cd loca_rep
   50.  cd local_rep
   51.  git init
   52.  ls -a
   53.  git branch -a
   54.  git branch
   55.  git config user.name "BrazovskyVladimir"
   56.  git config user.email "brazovsky@acdlabs.by"
   57.  date > master_date.txt
   58.  git status
   59.  echo $PATH > master_path.txt
   60.  git add master_date.txt
   61.  git status
   62.  git commmit
   63.  git commit -m "Commit master_date file"
   64.  git status
   65.  git add master_path.txt
   66.  git commit -m "Commit master_path file"
   67.  git status
   68.  git branch
   69.  git checkout -b dev
   70.  git branch -a
   71.  git log --oneline
   72.  date > dev_date.txt
   73.  echo $PATH > dev_path.txt
   74.  git log --oneline
   75.  git checkout master
   76.  git log --oneline
   77.  git checkout dev
   78.  git status
   79.  git add --all
   80.  git status
   81.  git rm --all
   82.  git rm dev_date.txt
   83.  git rm --cached
   84.  git rm --cached --all
   85.  git rm --cached dev_date.txt
   86.  git rm --cached path_date.txt
   87.  git status
   88.  git rm --cached dev_path.txt
   89.  git sttus
   90.  git status
   91.  git add dev_date.txt
   92.  git commit -m "Commit dev_date file"
   93.  git add dev_path.txt
   94.  git status
   95.  git commit -m "Commit dev_path file"
   96.  git log --oneline
   97.  git branch dev
   98.  git checkout -b features/do_one
   99.  date > feat_date_path.txt
  100.  echo $PATH >> feat_date_path.txt
  101.  git status
  102.  git add --all
  103.  git status
  104.  git commit -m "Commit feat_date_path file"
  105.  git branch -a
  106.  git branch master
  107.  git checkout master
  108.  git checkout dev
  109.  git checkout master
  110.  git checkout -b hotfix/we_gonna_die
  111.  git status
  112.  git branch
  113.  echo $PATH > hot_path_date.txt
  114.  echo $DATE >> hot_path_date.txt 
  115.  date >> hot_path_date.txt 
  116.  git status
  117.  git add --all
  118.  git status
  119.  git commit -m "Commit hot_path_date file"
  120.  git branch
  121.  git checkout dev
  122.  git branch
  123.  git checkout master
  124.  git merge hotfix/we_gonna_die
  125.  git status
  126.  git checkout dev
  127.  git merge features/do_one
  128.  git checkout master
  129.  git merge dev
  130.  git status
  131.  git branch
  132.  git log --oneline
  133.  git rebase -i HEAD~2
  134.  history
  135.  history > 02.Git.local.md
