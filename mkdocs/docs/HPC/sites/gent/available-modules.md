<pre><code>$ <b>module av | more</b>
--- /apps/gent/RHEL8/zen2-ib/modules/all ---
ABAQUS/2021-hotfix-2132
ABAQUS/2022-hotfix-2214
ABAQUS/2022
ABAQUS/2023                     (D)
ABINIT/9.2.1-intel-2020a
...
</code></pre>
The **`more`** command displays text one screen at a time. You can exit by entering **`q`**

Or when you want to check whether some specific software, some compiler or some
application (e.g., MATLAB) is installed on the {{hpc}}.

<pre><code>$ <b>module av | grep -i -e "matlab"</b>
MATLAB/2019b
MATLAB/2021b
MATLAB/2022b-r5
</code></pre>

As you are not aware of the capitals letters in the module name, we looked for
a case-insensitive name with the "-i" option.
