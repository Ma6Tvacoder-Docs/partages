                                                                   
C:\Users\Etudiant                                                  
λ cd../..                                                          
                                                                   
C:\                                                                
λ cd xampp\htdocs\github\partages\                                 
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git checkout -b stevymak-master master                           
Switched to a new branch 'stevymak-master'                         
                                                                   
C:\xampp\htdocs\github\partages (stevymak-master)                  
λ git pull https://github.com/stevymak/partages.git                
remote: Counting objects: 3, done.                                 
remote: Total 3 (delta 2), reused 2 (delta 2), pack-reused 1       
Unpacking objects: 100% (3/3), done.                               
From https://github.com/stevymak/partages                          
 * branch            HEAD       -> FETCH_HEAD                      
Auto-merging html/html_stevy.md                                    
Merge made by the 'recursive' strategy.                            
 html/html_stevy.md | 4 ++--                                       
 1 file changed, 2 insertions(+), 2 deletions(-)                   
                                                                   
C:\xampp\htdocs\github\partages (stevymak-master)                  
λ git checkout master                                              
Your branch is up-to-date with 'origin/master'.                    
Switched to branch 'master'                                        
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git merge --no-ff stevymak-master                                
Merge made by the 'recursive' strategy.                            
 html/html_stevy.md | 4 ++--                                       
 1 file changed, 2 insertions(+), 2 deletions(-)                   
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git push origin master                                           
To https://github.com/Ma6Tvacoder-Docs/partages.git                
 ! [rejected]        master -> master (fetch first)                
error: failed to push some refs to 'https://github.com/Ma6Tvacoder-
Docs/partages.git'                                                 
hint: Updates were rejected because the remote contains work that y
ou do                                                              
hint: not have locally. This is usually caused by another repositor
y pushing                                                          
hint: to the same ref. You may want to first integrate the remote c
hanges                                                             
hint: (e.g., 'git pull ...') before pushing again.                 
hint: See the 'Note about fast-forwards' in 'git push --help' for d
etails.                                                            
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git status                                                       
On branch master                                                   
Your branch is ahead of 'origin/master' by 3 commits.              
  (use "git push" to publish your local commits)                   
nothing to commit, working tree clean                              
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git checkout -b sylla380-master master                           
Switched to a new branch 'sylla380-master'                         
                                                                   
C:\xampp\htdocs\github\partages (sylla380-master)                  
λ git pull https://github.com/sylla380/partages.git master         
remote: Counting objects: 6, done.                                 
remote: Total 6 (delta 4), reused 4 (delta 4), pack-reused 2       
Unpacking objects: 100% (6/6), done.                               
From https://github.com/sylla380/partages                          
 * branch            master     -> FETCH_HEAD                      
Auto-merging html/CODAGE_HTML.MD                                   
Merge made by the 'recursive' strategy.                            
 html/CODAGE_HTML.MD | 2 ++                                        
 1 file changed, 2 insertions(+)                                   
                                                                   
C:\xampp\htdocs\github\partages (sylla380-master)                  
λ git checkout master                                              
Your branch and 'origin/master' have diverged,                     
and have 3 and 69 different commits each, respectively.            
  (use "git pull" to merge the remote branch into yours)           
Switched to branch 'master'                                        
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git merge --no-ff sylla380-master                                
Merge made by the 'recursive' strategy.                            
 html/CODAGE_HTML.MD | 2 ++                                        
 1 file changed, 2 insertions(+)                                   
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git push origin master                                           
To https://github.com/Ma6Tvacoder-Docs/partages.git                
 ! [rejected]        master -> master (non-fast-forward)           
error: failed to push some refs to 'https://github.com/Ma6Tvacoder-
Docs/partages.git'                                                 
hint: Updates were rejected because the tip of your current branch 
is behind                                                          
hint: its remote counterpart. Integrate the remote changes (e.g.   
hint: 'git pull ...') before pushing again.                        
hint: See the 'Note about fast-forwards' in 'git push --help' for d
etails.                                                            
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git pull origin master                                           
From https://github.com/Ma6Tvacoder-Docs/partages                  
 * branch            master     -> FETCH_HEAD                      
Merge made by the 'recursive' strategy.                            
 html/html_Ali.md             |   8 +++                            
 html/html_ali.html           | 142 +++++++++++++++++++++++++++++++
++++++++++++                                                       
 html/html_catherine.md       |   5 +-                             
 html_Ali.md                  |   8 +++                            
 sites_web.md                 |   9 ++-                            
 supports/github_gitkraken.md |  58 ++++++++++++++++++             
 6 files changed, 228 insertions(+), 2 deletions(-)                
 create mode 100644 html/html_Ali.md                               
 create mode 100644 html/html_ali.html                             
 create mode 100644 html_Ali.md                                    
 create mode 100644 supports/github_gitkraken.md                   
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git push origin master                                           
Counting objects: 20, done.                                        
Delta compression using up to 4 threads.                           
Compressing objects: 100% (20/20), done.                           
Writing objects: 100% (20/20), 2.15 KiB | 0 bytes/s, done.         
Total 20 (delta 14), reused 0 (delta 0)                            
remote: Resolving deltas: 100% (14/14), completed with 8 local obje
cts.                                                               
To https://github.com/Ma6Tvacoder-Docs/partages.git                
   df7502d..6d947c6  master -> master                              
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ git status                                                       
On branch master                                                   
Your branch is up-to-date with 'origin/master'.                    
nothing to commit, working tree clean                              
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ dir                                                              
 Le volume dans le lecteur C s’appelle Windows                     
 Le numéro de série du volume est 74F6-77D4                        
                                                                   
 Répertoire de C:\xampp\htdocs\github\partages                     
                                                                   
01/02/2017  11:23    <DIR>          .                              
01/02/2017  11:23    <DIR>          ..                             
01/02/2017  09:51    <DIR>          html                           
01/02/2017  09:51               327 html_Ali.md                    
31/01/2017  09:58    <DIR>          newsletter                     
25/01/2017  14:33               167 README.md                      
01/02/2017  11:23             3 429 sites_web.md                   
01/02/2017  09:51    <DIR>          supports                       
27/01/2017  13:04             6 063 veille.md                      
               4 fichier(s)            9 986 octets                
               5 Rép(s)  71 804 190 720 octets libres              
                                                                   
C:\xampp\htdocs\github\partages (master)                           
λ cd..                                                             
                                                                   
C:\xampp\htdocs\github                                             
λ dir                                                              
 Le volume dans le lecteur C s’appelle Windows                     
 Le numéro de série du volume est 74F6-77D4                        
                                                                   
 Répertoire de C:\xampp\htdocs\github                              
                                                                   
31/01/2017  09:54    <DIR>          .                              
31/01/2017  09:54    <DIR>          ..                             
01/02/2017  11:23    <DIR>          partages                       
               0 fichier(s)                0 octets                
               3 Rép(s)  71 804 190 720 octets libres              
                                                                   
C:\xampp\htdocs\github                                             
λ git clone https://github.com/MilaHG/fantome.git                  
Cloning into 'fantome'...                                          
remote: Counting objects: 9, done.                                 
remote: Compressing objects: 100% (5/5), done.                     
remote: Total 9 (delta 1), reused 0 (delta 0), pack-reused 0       
Unpacking objects: 100% (9/9), done.                               
                                                                   
C:\xampp\htdocs\github                                             
λ dir                                                              
 Le volume dans le lecteur C s’appelle Windows                     
 Le numéro de série du volume est 74F6-77D4                        
                                                                   
 Répertoire de C:\xampp\htdocs\github                              
                                                                   
01/02/2017  11:28    <DIR>          .                              
01/02/2017  11:28    <DIR>          ..                             
01/02/2017  11:28    <DIR>          fantome                        
01/02/2017  11:23    <DIR>          partages                       
               0 fichier(s)                0 octets                
               4 Rép(s)  71 803 559 936 octets libres              
                                                                   
C:\xampp\htdocs\github                                             
λ cd fantome\                                                      
                                                                   
C:\xampp\htdocs\github\fantome (master)                            
λ git status                                                       
On branch master                                                   
Your branch is up-to-date with 'origin/master'.                    
nothing to commit, working tree clean                              
                                                                   
C:\xampp\htdocs\github\fantome (master)                            
λ dir                                                              
 Le volume dans le lecteur C s’appelle Windows                     
 Le numéro de série du volume est 74F6-77D4                        
                                                                   
 Répertoire de C:\xampp\htdocs\github\fantome                      
                                                                   
01/02/2017  11:28    <DIR>          .                              
01/02/2017  11:28    <DIR>          ..                             
01/02/2017  11:28                20 fantome02.md                   
01/02/2017  11:28                50 fantome1.md                    
01/02/2017  11:28                46 README.md                      
               3 fichier(s)              116 octets                
               2 Rép(s)  71 803 559 936 octets libres              
                                                                   
C:\xampp\htdocs\github\fantome (master)                            
λ mkdir fantome3.md                                                
                                                                   
C:\xampp\htdocs\github\fantome (master)                            
λ mkdir fantome3.md                                                
                                                                   
C:\xampp\htdocs\github\fantome (master)                            
λ  cd fantome3.md\                                                 
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ dir                                                              
 Le volume dans le lecteur C s’appelle Windows                     
 Le numéro de série du volume est 74F6-77D4                        
                                                                   
 Répertoire de C:\xampp\htdocs\github\fantome\fantome3.md          
                                                                   
01/02/2017  11:30    <DIR>          .                              
01/02/2017  11:30    <DIR>          ..                             
               0 fichier(s)                0 octets                
               2 Rép(s)  71 803 555 840 octets libres              
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ touch fantomette.html                                            
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ git add *                                                        
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ git commit -m "creation dossier fantome3"                        
[master 9a048f5] creation dossier fantome3                         
 1 file changed, 0 insertions(+), 0 deletions(-)                   
 create mode 100644 fantome3.md/fantomette.html                    
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ git push origin master                                           
Counting objects: 4, done.                                         
Delta compression using up to 4 threads.                           
Compressing objects: 100% (2/2), done.                             
Writing objects: 100% (4/4), 327 bytes | 0 bytes/s, done.          
Total 4 (delta 1), reused 0 (delta 0)                              
remote: Resolving deltas: 100% (1/1), completed with 1 local object
s.                                                                 
To https://github.com/MilaHG/fantome.git                           
   4dbf62c..9a048f5  master -> master                              
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ git pull origin master                                           
remote: Counting objects: 4, done.                                 
remote: Compressing objects: 100% (3/3), done.                     
remote: Total 4 (delta 1), reused 0 (delta 0), pack-reused 0       
Unpacking objects: 100% (4/4), done.                               
From https://github.com/MilaHG/fantome                             
 * branch            master     -> FETCH_HEAD                      
   9a048f5..f320690  master     -> origin/master                   
Updating 9a048f5..f320690                                          
Fast-forward                                                       
 fantome3.md/fantomette.html | 107 ++++++++++++++++++++++++++++++++
++++++++++++                                                       
 1 file changed, 107 insertions(+)                                 
                                                                   
C:\xampp\htdocs\github\fantome\fantome3.md (master)                
λ                                                                  
                                                                   
                                                                   
                                                                   
                                                                   
                                                                   
                                                                   
