<table width="100%" id="gittable" class="dataTable no-footer" role="grid" aria-describedby="gittable_info">
            <thead>
            <tr role="row"><th width="10" class="sorting_asc" tabindex="0" aria-controls="gittable" rowspan="1" colspan="1" aria-sort="ascending" aria-label="Serial: activate to sort column descending">Serial</th><th width="35" class="sorting" tabindex="0" aria-controls="gittable" rowspan="1" colspan="1" aria-label="Git Command: activate to sort column ascending">Git Command</th><th width="35%" class="sorting" tabindex="0" aria-controls="gittable" rowspan="1" colspan="1" aria-label="Description: activate to sort column ascending">Description</th><th width="20%" class="sorting" tabindex="0" aria-controls="gittable" rowspan="1" colspan="1" aria-label="Tags: activate to sort column ascending">Tags</th></tr>
            </thead>
            <tbody>
            <tr role="row" class="odd">
                <td class="sorting_1">1</td>
                <td>git init</td>
                <td>Initialize git repository in a folder</td>
                <td>init,start git,open git</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">2</td>
                <td id="gitconfig">git status</td>
                <td>Information about changed/deleted files</td>
                <td>status,condition,changes,modify</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">3</td>
                <td>git config username.name Jhon</td>
                <td>Config git user for the current git</td>
                <td>git, config, user,name</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">4</td>
                <td>git config username.email jhon@gmail.com</td>
                <td>Config git email for the current git</td>
                <td>git, config, user,email</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">5</td>
                <td>git config --global username.name Jhon</td>
                <td>Config git user for the current git globally in a machine</td>
                <td>setup,config, globally, user,name</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">6</td>
                <td>git config --global username.email jd@gmail.com</td>
                <td>Config git email for the current git globally in a machine</td>
                <td>setup,config, globally, user,email</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">7</td>
                <td style="font-size: 13px;">git remote add origin https://example.com</td>
                <td>Config remote connection for uploading files and data to the repository(such as github, gitlab,
                    bitbucket, sourceforge)
                </td>
                <td>setup,origin,remote,server,repo</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">8</td>
                <td>git -v</td>
                <td>Current installed git version</td>
                <td>git,version,show</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">9</td>
                <td>git add file.txt</td>
                <td>Add specific file for commit</td>
                <td>add, fixed, specific, custom file</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">10</td>
                <td>git add &nbsp; .</td>
                <td>Add all changed file for commit</td>
                <td>add, all, every file, changed</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">11</td>
                <td>git commit -m "commit message"</td>
                <td>Commit Changes with messages and information</td>
                <td>commit, change, -m</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">12</td>
                <td id="gitbranch">git branch</td>
                <td>See all local branch list</td>
                <td>branch, list, local</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">13</td>
                <td id="gitbranch">git branch -a</td>
                <td>See all local and remote branch</td>
                <td>branch,remote, list,all, local</td>
            </tr><tr role="row" class="even"><td class="sorting_1">14</td>
            <td id="gitbranch">git branch -r</td>
            <td>See all remote branch list</td>
            <td>remote,all, list,branch</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">15</td>
                <td title="">git branch branch_name</td>
                <td>Create new branch locally</td>
                <td>branch, change, make, create</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">16</td>
                <td>git checkout -b branch_name</td>
                <td>Create new branch and move to there</td>
                <td>create, move, branch, checkout</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">17</td>
                <td title="">
                    git checkout -b branch_name <br>or<br>
                    git push origin branch_name
                </td>
                <td>Create new branch locally and push it to origin</td>
                <td>branch, change, make, create</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">18</td>
                <td title="for migrating to any branch use git checkout branch_name">git checkout dev</td>
                <td title="here dev is a custom branch for example purpose">Migrate from any branch to dev</td>
                <td>create, move, branch, checkout</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">19</td>
                <td title="for migrating to any branch use git checkout branch_name">git branch -D branch_name</td>
                <td title="here dev is a custom branch for example purpose">Delete local branch</td>
                <td>delete, local, branch, repo</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">20</td>
                <td title="for migrating to any branch use git checkout branch_name">git push --delete origin
                    branch_name
                </td>
                <td title="here dev is a custom branch for example purpose">Delete branch from remote</td>
                <td>delete, origin, branch, checkout</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">21</td>
                <td title="">git push</td>
                <td>Push current changed commits to current branch where you are</td>
                <td>push, commit, master</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">22</td>
                <td title="">git push -u origin master</td>
                <td>Push current changed commits to master branch</td>
                <td>push, commit, change,master</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">23</td>
                <td title="">git push -u origin branch_name</td>
                <td>Push current changed commits to specific branch</td>
                <td>specific,fixpush,branch,commit, change,master</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">24</td>
                <td title="">git log</td>
                <td>show all commits with details</td>
                <td>git,log, change, commit,all</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">25</td>
                <td title="" id="gitlog">git log --oneline</td>
                <td>show all commits with summary</td>
                <td>log,change,commit,summary</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">26</td>
                <td title="">git rev-list --all</td>
                <td>show all commits with commit long id</td>
                <td>git,log, change, commit,all</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">27</td>
                <td title="">git rev-list --all --count</td>
                <td>Show number of commits</td>
                <td>count, number, how many, log</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">28</td>
                <td title="">git shortlog</td>
                <td>Show number of commits with summary</td>
                <td>log,number,commit,list</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">29</td>
                <td title="">git shortlog -s</td>
                <td>Show number of commits per user</td>
                <td>user,commit,change,log,list,count,number</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">30</td>
                <td id="gittag">git pull</td>
                <td>update local branch by fetching data from remote origin</td>
                <td>pull, update,remote ,origin</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">31</td>
                <td>git tag</td>
                <td>Show all local tag list</td>
                <td>tag, list, all, tags</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">32</td>
                <td>git ls-remote --tags origin</td>
                <td>Show all remote tag list</td>
                <td>tag, list,remote, origin, all, tags</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">33</td>
                <td>git tag tag_name</td>
                <td>Create a new tag locally</td>
                <td>tag, create, new, local</td>
            </tr><tr id="push" role="row" class="even">
                <td class="sorting_1">34</td>
                <td>git checkout tags/tagname</td>
                <td>Checkout to new tag</td>
                <td>tag, checkout, new,</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">35</td>
                <td>git tag tag_name -a<br>or<br>git push origin --tags</td>
                <td>Create a local tag and upload to origin</td>
                <td>origin, tag, remote</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">36</td>
                <td>git push --tags</td>
                <td>Push all tags to the remote</td>
                <td>push, tag, all, --tags</td>
            </tr><tr id="push" role="row" class="odd">
                <td class="sorting_1">37</td>
                <td>git tag tag_name -a</td>
                <td>Create a new tag with nesscessary description</td>
                <td>-a, tag,create, make</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">38</td>
                <td>git tag -d tag_name</td>
                <td>Delete local tag</td>
                <td>tag,delete,clear, local</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">39</td>
                <td style="font-size: 13px;">git push origin :tagname<br>or<br>git push --delete origin tagname <br>or
                    <br> git push origin :refs/tags/tagname
                </td>
                <td>Delete remote tag</td>
                <td>tag, delete, push, origin</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">40</td>
                <td>git fetch --tags</td>
                <td>Fetch and update local tags from remote origin</td>
                <td>tag,fetch,remote,origin</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">41</td>
                <td>git merge feature</td>
                <td>Merge master branch with feature sub brach</td>
                <td>master,rebase, feature,sub, child</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">42</td>
                <td>git rebase feature</td>
                <td>Rebase feature branch with master branch</td>
                <td>rebase, feature, master, merge, change</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">43</td>
                <td>git push -u --all</td>
                <td>Push Branch on Remote</td>
                <td>push, branch, remote</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">44</td>
                <td>git reset</td>
                <td>Unstage All Added Before Commit Done</td>
                <td>stage, unstage, git, commit</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">45</td>
                <td>git reset --hard HEAD</td>
                <td>Delete last commit and return to code</td>
                <td>code, last, commit, code</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">46</td>
                <td>git reset --soft HEAD</td>
                <td>Delete commit and save changes</td>
                <td>code, last, commit, change</td>
            </tr><tr id="bottom" role="row" class="odd">
                <td class="sorting_1">47</td>
                <td>git rm --cached filename</td>
                <td>Remove specific file from git cache</td>
                <td>cache, remove, git, fixed,file</td>
            </tr><tr role="row" class="even">
                <td class="sorting_1">48</td>
                <td>git rm -r --cached .</td>
                <td>Remove all files from git cache</td>
                <td>cache,all,remove,files</td>
            </tr><tr role="row" class="odd">
                <td class="sorting_1">49</td>
                <td>git reset --hard HEAD~1</td>
                <td>Remove last commit from local</td>
                <td>Remove last commit</td>
            </tr>
            <tr role="row" class="even">
                <td class="sorting_1">50</td>
                <td>git push -f origin master</td>
                <td>Push change to remote</td>
                <td>Push to remove</td>
            </tr>
            <tr role="row" class="even">
                <td class="sorting_1">51</td>
                <td>git checkout <commit_id></td>
                <td>The git checkout command in Git is used to switch between different branches or commits</td>
                <td>Switch between different commits</td>
            </tr>
        </tbody>
        </table>
