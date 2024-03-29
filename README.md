# linlab

# 2019-09-23 组蛋白修饰
组蛋白修饰(histone modification)是指组蛋白在相关酶作用下，N端尾部氨基酸发生甲基化(methylation, M)、乙酰化(acetylation, Ac)、磷酸化(phosphorylation, P)、泛素化(ubiquitination)、ADP核糖基化(ADP-ribosylation)等修饰，调控染色质的结构和组成，直接影响转录因子与基因启动子的结合而调节基因表达的活化或沉默。

  <table width="895" border="0" cellpadding="0" cellspacing="0" style='width:447.50pt;border-collapse:collapse;table-layout:fixed;'>
   <col width="194" style='mso-width-source:userset;mso-width-alt:4729;'/>
   <col width="168" style='mso-width-source:userset;mso-width-alt:4095;'/>
   <col width="171" style='mso-width-source:userset;mso-width-alt:4168;'/>
   <col width="362" style='mso-width-source:userset;mso-width-alt:8825;'/>
   <tr height="50" style='height:25.00pt;mso-height-source:userset;mso-height-alt:500;'>
    <td class="xl65" height="50" width="194" style='height:25.00pt;width:97.00pt;'></td>
    <td class="xl65" width="168" style='width:84.00pt;' x:str>修饰的类型</td>
    <td class="xl65" width="171" style='width:85.50pt;' x:str>对转录的作用</td>
    <td class="xl65" width="362" style='width:181.00pt;' x:str>组蛋白修饰位点</td>
   </tr>
   <tr height="98" style='height:49.00pt;mso-height-source:userset;mso-height-alt:980;'>
    <td class="xl65" height="382" rowspan="5" style='height:191.00pt;border-right:none;border-bottom:none;' x:str>小分子基团修饰</td>
    <td class="xl65" x:str>乙酰化(可逆)</td>
    <td class="xl65" x:str>激活</td>
    <td class="xl65" x:str>H3(K9, K14, K18, K23); H4(K5, K8, K12, K16); H2A(K5, K9); H2B(K5, K12, K15, K20)</td>
   </tr>
   <tr height="84" style='height:42.00pt;mso-height-source:userset;mso-height-alt:840;'>
    <td class="xl65" rowspan="2" style='border-right:none;border-bottom:none;' x:str>甲基化(可逆)</td>
    <td class="xl65" x:str>激活</td>
    <td class="xl65" x:str>H3(K4, K36, K79)</td>
   </tr>
   <tr height="66" style='height:33.00pt;mso-height-source:userset;mso-height-alt:660;'>
    <td class="xl65" x:str>抑制</td>
    <td class="xl65" x:str>H3(K9, K27); H4(K20)</td>
   </tr>
   <tr height="68" style='height:34.00pt;mso-height-source:userset;mso-height-alt:680;'>
    <td class="xl65" rowspan="2" style='border-right:none;border-bottom:none;' x:str>磷酸化</td>
    <td class="xl65" x:str>激活</td>
    <td class="xl65" x:str>H3(S10)</td>
   </tr>
   <tr height="66" style='height:33.00pt;mso-height-source:userset;mso-height-alt:660;'>
    <td class="xl65" x:str>抑制</td>
    <td class="xl65" x:str>H2A(S1)</td>
   </tr>
   <tr height="72" style='height:36.00pt;mso-height-source:userset;mso-height-alt:720;'>
    <td class="xl65" height="224" rowspan="3" style='height:112.00pt;border-right:none;border-bottom:none;' x:str>肽类修饰</td>
    <td class="xl65" rowspan="2" style='border-right:none;border-bottom:none;' x:str>泛素化</td>
    <td class="xl65" x:str>激活</td>
    <td class="xl65" x:str>H2B(K123)</td>
   </tr>
   <tr height="56" style='height:28.00pt;mso-height-source:userset;mso-height-alt:560;'>
    <td class="xl65" x:str>抑制</td>
    <td class="xl65" x:str>H2A(K119)</td>
   </tr>
   <tr height="96" style='height:48.00pt;mso-height-source:userset;mso-height-alt:960;'>
    <td class="xl65" x:str>SUMO化</td>
    <td class="xl65" x:str>抑制</td>
    <td class="xl65" x:str>H4(K5, K8, K12, K16); H2A(K126); H2B(K6, K7, K16, K17)</td>
   </tr>
   <![if supportMisalignedColumns]>
    <tr width="0" style='display:none;'>
     <td width="194" style='width:97;'></td>
     <td width="168" style='width:84;'></td>
     <td width="171" style='width:86;'></td>
     <td width="362" style='width:181;'></td>
    </tr>
   <![endif]>
  </table>

## 组蛋白乙酰化：
这是由组蛋白乙酰转移酶(histone acetyltransferase，HAT)和组蛋白去乙酰化酶(histone deacetylase, HDAC)协调催化进行的一个可逆动态过程。组蛋白乙酰化修饰一般与基因转录激活相关，而组蛋白去乙酰化则与基因沉默相关。

机制：乙酰化的N端携带的正电荷减少，导致组蛋白八聚体与DNA结合的稳定性降低，并且核小体排列的紧密程度也降低，便于转录因子、RNA聚合酶等与转录相关的蛋白质与启动子等调控序列的结合。

## 组蛋白甲基化：
* 组蛋白赖氨酸甲基化由特异的组蛋白赖氨酸甲基转移酶(histonelysine(K)methyltransferase, HKMT)催化，组蛋白精氨酸甲基化则由特异的蛋白质精氨酸甲基转移酶(protein-arginine(R)methyltransferase, PRMT)催化。
* 甲基化修饰位点不同，且每个残基的甲基化程度也不同，赖氨酸(K)可以被单(me1), 双(me2)或三(me3)甲基化，精氨酸(R)也存在me1和me2甲基化。
*  组蛋白甲基化修饰既与基因的转录抑制相关，又与转录激活相关，这取决于被修饰的氨基酸残基所处的位置、被修饰的程度，以及甲基转移酶的性质。
    * 就赖氨酸残基而言，一般H3K4、H3K36、H3K79的甲基化与转录激活相关，而H3K9、H3K27、H4K20的甲基化则与转录抑制相关。
    * 就精氨酸残基的甲基化修饰而言，PRMT1催化H4R3甲基化，而PRMT4/CARM1催化H3R2、H3R17和H3R26的甲基化，这两个甲基化酶与转录激活相关；PRMT5可甲基化H3R8和H4R3，与转录抑制有关。

## 组蛋白泛素化：
泛素化(ubiquitinoylation,  Ub)是多种酶共同参与的级联酶促反应过程。染色质核心组蛋白泛素化修饰多属于单泛素化修饰，参与基因表达的染色质调控和DNA复制等过程。组蛋白H2AK119Ub和H2BK123Ub的单泛素化分别对基因转录起抑制作用和激活作用。

机制：
* 改变了染色质结构使DNA暴露而激活转录
* 作为募集其它转录因子的信号激活或抑制转录
* 通过影响其它类型的共价修饰而调节基因转录

## 组蛋白磷酸化：
核心组蛋白的磷酸化是细胞分裂中染色体凝缩、转录调控和DNA损伤修复的关键中间步骤。磷酸化能破坏组蛋白与DNA间的相互作用，使染色质结构不稳定。

机制：
* 磷酸基团携带的负电荷中和了组蛋白上的正电荷，造成组蛋白与DNA之间的亲和力下降。
* 修饰能够产生与蛋白识别模块结合的表面，与特异的蛋白质复合物相互作用。
