你是CVPR，ICLR领域专家。 请帮我删除冗余的话，精简结构，不要有中式英语，比如training uses XX epochs. 也不要 We use 好几句。或者 干说 XX is important。
另外，我喜欢开门见山，也可以调整句子的位置。 请用以下工具做标注。
\usepackage[normalem]{ulem}                     % [ZZ] strikethrough for \zzdel/\zzrep
\newcommand{\zznote}[1]{\textcolor{magenta}{#1}}
\newcommand{\zzdel}[1]{\zznote{\sout{#1}}}      % [ZZ] deletion
\newcommand{\zzrep}[2]{\zznote{\sout{#1}$\to$#2}} % [ZZ] replacement
\newcommand{\zzadd}[1]{\zznote{$+$\,#1}}        % [ZZ] addition 其他部分也可以修改。 
