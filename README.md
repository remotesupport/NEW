<xml xmlns="http://www.w3.org/1999/xhtml" collection="true">
  <block type="procedures_defreturn" id="qq2xGirc*Byb/P/HE^]H" collapsed="true" x="0" y="0">
    <field name="NAME">D'Alembert Trade Amount</field>
    <comment pinned="false" h="80" w="160">Describe this function...</comment>
    <statement name="STACK">
      <block type="controls_if" id="n4tz9*`uW5vI{Y(mwC)L">
        <value name="IF0">
          <block type="logic_compare" id="3qWA5gevZ|UpE{.gFl4n">
            <field name="OP">EQ</field>
            <value name="A">
              <block type="variables_get" id="nXPxXCq9p:hf1Xx:`D_{">
                <field name="VAR">dalembert:expectedProfit</field>
              </block>
            </value>
            <value name="B">
              <block type="logic_null" id="Tp8pr^]@7PA~eGl`XK?b"></block>
            </value>
          </block>
        </value>
        <statement name="DO0">
          <block type="variables_set" id="p8_@*8We560p~d]XEj-I">
            <field name="VAR">dalembert:expectedProfit</field>
            <value name="VALUE">
              <block type="text_prompt_ext" id="%r0#U,KXY;)S1-I},GCs">
                <mutation type="NUMBER"></mutation>
                <field name="TYPE">NUMBER</field>
                <value name="TEXT">
                  <shadow type="text" id=".P`a1!r=yj-[H(SJX}_m">
                    <field name="TEXT">abc</field>
                  </shadow>
                  <block type="text" id="AlB(yFhIT1/FZu-ZEpqQ">
                    <field name="TEXT">Expected Profit</field>
                  </block>
                </value>
              </block>
            </value>
          </block>
        </statement>
        <next>
          <block type="controls_if" id="qa:)sj8|A!lxwG*|YaO]">
            <value name="IF0">
              <block type="logic_compare" id="fo(G)bKdQhx,?aEY[Yl}">
                <field name="OP">EQ</field>
                <value name="A">
                  <block type="variables_get" id="`Geg[{!:(HTr6q)A];`0">
                    <field name="VAR">dalembert:maximumLoss</field>
                  </block>
                </value>
                <value name="B">
                  <block type="logic_null" id="!X8^fykpJtsH#Il8+Wh9"></block>
                </value>
              </block>
            </value>
            <statement name="DO0">
              <block type="variables_set" id="t3Gw#E]HVqIM/6J-t-2Y">
                <field name="VAR">dalembert:maximumLoss</field>
                <value name="VALUE">
                  <block type="text_prompt_ext" id="K[Cz2)F(1ny#Zw!j7j!V">
                    <mutation type="NUMBER"></mutation>
                    <field name="TYPE">NUMBER</field>
                    <value name="TEXT">
                      <shadow type="text" id=".P`a1!r=yj-[H(SJX}_m">
                        <field name="TEXT">abc</field>
                      </shadow>
                      <block type="text" id="dfNPxr:VpC%uF[yz%xk[">
                        <field name="TEXT">Maximum Loss Amount</field>
                      </block>
                    </value>
                  </block>
                </value>
              </block>
            </statement>
            <next>
              <block type="controls_if" id="^CEM+~9aQ2uhnXtkL`kv">
                <value name="IF0">
                  <block type="logic_compare" id="wL4k~{ia}[/ON_+z47RO">
                    <field name="OP">EQ</field>
                    <value name="A">
                      <block type="variables_get" id="WjGS@!}HI|kFH{rJqavk">
                        <field name="VAR">dalembert:amount</field>
                      </block>
                    </value>
                    <value name="B">
                      <block type="logic_null" id="qTK#~^WMVK;Wyz1LJ/@d"></block>
                    </value>
                  </block>
                </value>
                <statement name="DO0">
                  <block type="variables_set" id="ZxKDnNw2?MsznEZQtR6`">
                    <field name="VAR">dalembert:amount</field>
                    <value name="VALUE">
                      <block type="text_prompt_ext" id="^4peSz1pJ=`,CaD#@6Jd">
                        <mutation type="NUMBER"></mutation>
                        <field name="TYPE">NUMBER</field>
                        <value name="TEXT">
                          <shadow type="text" id=".P`a1!r=yj-[H(SJX}_m">
                            <field name="TEXT">abc</field>
                          </shadow>
                          <block type="text" id="=6eX{Eblptb4BBlz7?U[">
                            <field name="TEXT">Trade Amount</field>
                          </block>
                        </value>
                      </block>
                    </value>
                  </block>
                </statement>
                <next>
                  <block type="controls_if" id="kC@O!Xl:KO^G_(uzKTzH">
                    <value name="IF0">
                      <block type="logic_compare" id="@|K%}q0X`VebpuZQ=EV*">
                        <field name="OP">EQ</field>
                        <value name="A">
                          <block type="variables_get" id="(xdUld=/ZoI`Y#*TZfMw">
                            <field name="VAR">dalembert:size</field>
                          </block>
                        </value>
                        <value name="B">
                          <block type="logic_null" id="CA@kQ}mQ:c8NW0=5Ed[."></block>
                        </value>
                      </block>
                    </value>
                    <statement name="DO0">
                      <block type="variables_set" id="^xOi2|SaRE2S4sk8(u74">
                        <field name="VAR">dalembert:size</field>
                        <value name="VALUE">
                          <block type="math_number" id="v]w4MInl_BA/~uV5yCK3">
                            <field name="NUM">1</field>
                          </block>
                        </value>
                      </block>
                    </statement>
                    <next>
                      <block type="controls_if" id="h,Nbdz7YuKUY`Gfbpf|m">
                        <value name="IF0">
                          <block type="logic_compare" id="sb^6?GtDqE1.gRR,o^6w">
                            <field name="OP">EQ</field>
                            <value name="A">
                              <block type="variables_get" id="Af?3G/kU#Zr*:F:)!TXF">
                                <field name="VAR">dalembert:profitUnits</field>
                              </block>
                            </value>
                            <value name="B">
                              <block type="logic_null" id="bQQ+#eD?`3tP=4tI@B9S"></block>
                            </value>
                          </block>
                        </value>
                        <statement name="DO0">
                          <block type="variables_set" id="lw``#pLseumYH8FC2--~">
                            <field name="VAR">dalembert:profitUnits</field>
                            <value name="VALUE">
                              <block type="math_number" id="pOIB*s(LL2r5s}F#_Fs1">
                                <field name="NUM">0</field>
                              </block>
                            </value>
                          </block>
                        </statement>
                        <next>
                          <block type="controls_if" id="fwmgCgdRdN{)3S|t|fn7">
                            <value name="IF0">
                              <block type="logic_compare" id="pj:P)Py2NsbQ8@=5Y9D=">
                                <field name="OP">EQ</field>
                                <value name="A">
                                  <block type="variables_get" id="5A]k/?)Q#Xi4G,Wpd;Pz">
                                    <field name="VAR">dalembert:totalProfit</field>
                                  </block>
                                </value>
                                <value name="B">
                                  <block type="logic_null" id=";,X}K#n`DxM#4`t;d~Cc"></block>
                                </value>
                              </block>
                            </value>
                            <statement name="DO0">
                              <block type="variables_set" id="MmEFyqc*]VjjlJZzlNt[">
                                <field name="VAR">dalembert:totalProfit</field>
                                <value name="VALUE">
                                  <block type="math_number" id="DcgRnz]nVdJyT*eH=v!;">
                                    <field name="NUM">0</field>
                                  </block>
                                </value>
                              </block>
                            </statement>
                          </block>
                        </next>
                      </block>
                    </next>
                  </block>
                </next>
              </block>
            </next>
          </block>
        </next>
      </block>
    </statement>
    <value name="RETURN">
      <block type="math_arithmetic" id="9oY.1lAF`%[xoFKW!Vak">
        <field name="OP">MULTIPLY</field>
        <value name="A">
          <shadow type="math_number" id="!N5Q!/XB/Zq(Yh8GZNXa">
            <field name="NUM">1</field>
          </shadow>
          <block type="variables_get" id="Zb1gI0smw}o}MYn(O2z7">
            <field name="VAR">dalembert:size</field>
          </block>
        </value>
        <value name="B">
          <shadow type="math_number" id="_MIi~6{+puJoIPRIyX8S">
            <field name="NUM">1</field>
          </shadow>
          <block type="variables_get" id="dZh,rVm,Z,HL;@*{;ZGS">
            <field name="VAR">dalembert:amount</field>
          </block>
        </value>
      </block>
    </value>
  </block>
  <block type="procedures_defnoreturn" id="yNTO_g~CmG;eLIF(#(Fq" collapsed="true" x="0" y="52">
    <mutation>
      <arg name="dalembert:resultIsWin"></arg>
    </mutation>
    <field name="NAME">D'Alembert Core Functionality</field>
    <comment pinned="false" h="80" w="160">Describe this function...</comment>
    <statement name="STACK">
      <block type="controls_if" id="du_v/n9L4`|ArT@vt^u(">
        <mutation else="1"></mutation>
        <value name="IF0">
          <block type="variables_get" id="P]*Fp7~p#Lj1S#`(3rAr">
            <field name="VAR">dalembert:resultIsWin</field>
          </block>
        </value>
        <statement name="DO0">
          <block type="variables_set" id="!=lcrD.j^lG@TEIG!Wt+">
            <field name="VAR">dalembert:profitUnits</field>
            <value name="VALUE">
              <block type="math_arithmetic" id="TdC9Atw|9KH;~yI[5d-{">
                <field name="OP">ADD</field>
                <value name="A">
                  <shadow type="math_number" id="ZI-r}kzT8Y=p.GdTq7lH">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="variables_get" id="X7ro_Db;}l{v^YAzQBbu">
                    <field name="VAR">dalembert:profitUnits</field>
                  </block>
                </value>
                <value name="B">
                  <shadow type="math_number" id="{Y2dS`Z1{(w6k%yQoR~m">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="variables_get" id="^KQ1@hKbpC)EO-!1Vkh(">
                    <field name="VAR">dalembert:size</field>
                  </block>
                </value>
              </block>
            </value>
            <next>
              <block type="controls_if" id="T+LMuBa?y@W4es3Z}sjZ">
                <mutation else="1"></mutation>
                <value name="IF0">
                  <block type="logic_compare" id="~dgK]Iz*%C46;r+~8#}!">
                    <field name="OP">GT</field>
                    <value name="A">
                      <block type="variables_get" id="W2eGOw^LKa45XEtku6}W">
                        <field name="VAR">dalembert:size</field>
                      </block>
                    </value>
                    <value name="B">
                      <block type="math_number" id="#s1ADC9}k|_{6N3I*+|Y">
                        <field name="NUM">1</field>
                      </block>
                    </value>
                  </block>
                </value>
                <statement name="DO0">
                  <block type="variables_set" id="LUJS=P2(!/IWCRY:IsTl">
                    <field name="VAR">dalembert:size</field>
                    <value name="VALUE">
                      <block type="math_arithmetic" id="7#hL./MNVEX(Gb#D`~EC">
                        <field name="OP">MINUS</field>
                        <value name="A">
                          <shadow type="math_number" id="yo:WX(YXv,7m)@[dD*T6">
                            <field name="NUM">1</field>
                          </shadow>
                          <block type="variables_get" id="%:^P@RJGx^xUN2aftCd@">
                            <field name="VAR">dalembert:size</field>
                          </block>
                        </value>
                        <value name="B">
                          <shadow type="math_number" id="xWP@Cne~D[-/%I4}kMHm">
                            <field name="NUM">1</field>
                          </shadow>
                        </value>
                      </block>
                    </value>
                  </block>
                </statement>
                <statement name="ELSE">
                  <block type="variables_set" id="}HweP{]-KGldbObsN5ja">
                    <field name="VAR">dalembert:profitUnits</field>
                    <value name="VALUE">
                      <block type="math_number" id="F_|2V`E6ObE80k~?NztP">
                        <field name="NUM">0</field>
                      </block>
                    </value>
                    <next>
                      <block type="notify" id="#sbO?-oLMKqQZk(C3=v?">
                        <field name="NOTIFICATION_TYPE">success</field>
                        <value name="MESSAGE">
                          <block type="text" id="N0Ms_cA_dls{(fg4o]rE">
                            <field name="TEXT">One DAlembert session finished successfully.</field>
                          </block>
                        </value>
                      </block>
                    </next>
                  </block>
                </statement>
              </block>
            </next>
          </block>
        </statement>
        <statement name="ELSE">
          <block type="variables_set" id="/-d0;K+{pd79q%;p^o6!">
            <field name="VAR">dalembert:profitUnits</field>
            <value name="VALUE">
              <block type="math_arithmetic" id="^1(jnI}%J5*f^qdE~e%!">
                <field name="OP">MINUS</field>
                <value name="A">
                  <shadow type="math_number" id="ZI-r}kzT8Y=p.GdTq7lH">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="variables_get" id="uI[tG5Ijf_[ihid2hC0t">
                    <field name="VAR">dalembert:profitUnits</field>
                  </block>
                </value>
                <value name="B">
                  <shadow type="math_number" id="{Y2dS`Z1{(w6k%yQoR~m">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="variables_get" id=":yC#6A!Y3xuMNiwm-fdB">
                    <field name="VAR">dalembert:size</field>
                  </block>
                </value>
              </block>
            </value>
            <next>
              <block type="variables_set" id="?QPU}PR2doaiC^[4f2(d">
                <field name="VAR">dalembert:size</field>
                <value name="VALUE">
                  <block type="math_arithmetic" id="{p%YL?+Yk3!+=*tM_dR/">
                    <field name="OP">ADD</field>
                    <value name="A">
                      <shadow type="math_number" id="yo:WX(YXv,7m)@[dD*T6">
                        <field name="NUM">1</field>
                      </shadow>
                      <block type="variables_get" id="cp=ul.-FT,41`IF2Gzix">
                        <field name="VAR">dalembert:size</field>
                      </block>
                    </value>
                    <value name="B">
                      <shadow type="math_number" id="X@amaJRGiwc^;5j.8f4T">
                        <field name="NUM">1</field>
                      </shadow>
                    </value>
                  </block>
                </value>
              </block>
            </next>
          </block>
        </statement>
      </block>
    </statement>
  </block>
  <block type="procedures_defreturn" id="_b//g0Q,2OW8MbY^`J3E" collapsed="true" x="0" y="104">
    <mutation>
      <arg name="dalembert:profit"></arg>
      <arg name="dalembert:resultIsWin"></arg>
    </mutation>
    <field name="NAME">D'Alembert Trade Again After Purchase</field>
    <comment pinned="false" h="80" w="160">Describe this function...</comment>
    <statement name="STACK">
      <block type="math_change" id="5ph^#sJ_|cnLn{}e(%Z{">
        <field name="VAR">dalembert:totalProfit</field>
        <value name="DELTA">
          <shadow type="math_number" id="[)Nh?MH}TXeN]0n(Q?PP">
            <field name="NUM">1</field>
          </shadow>
          <block type="variables_get" id="Kj+o2HPe^1#-J*pl.VD9">
            <field name="VAR">dalembert:profit</field>
          </block>
        </value>
        <next>
          <block type="variables_set" id="=``}2YqGE51x5XO#O{A6">
            <field name="VAR">dalembert:totalProfit</field>
            <value name="VALUE">
              <block type="math_arithmetic" id="m9HUE{JvBzON.?`k.p0L">
                <field name="OP">DIVIDE</field>
                <value name="A">
                  <shadow type="math_number" id="Y445k*N9Y{3k^0nU:f/a">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="math_round" id="eOhznKTK*Yn[R~s!l7p;">
                    <field name="OP">ROUND</field>
                    <value name="NUM">
                      <shadow type="math_number" id="NxI4W6P)%aS~YX^5:fm(">
                        <field name="NUM">3.1</field>
                      </shadow>
                      <block type="math_arithmetic" id="a52-x:2(jo3fN-]co/k]">
                        <field name="OP">MULTIPLY</field>
                        <value name="A">
                          <shadow type="math_number" id="1IiDMd{pA4I8#Jv5:v)F">
                            <field name="NUM">1</field>
                          </shadow>
                          <block type="variables_get" id="djyZC:DVv!8AFfC.FoYS">
                            <field name="VAR">dalembert:totalProfit</field>
                          </block>
                        </value>
                        <value name="B">
                          <shadow type="math_number" id="QPp6Ex`FL}B)uWsSrQ*o">
                            <field name="NUM">1</field>
                          </shadow>
                          <block type="math_number" id="qdaI}RV~2ic%D1==.15s">
                            <field name="NUM">100</field>
                          </block>
                        </value>
                      </block>
                    </value>
                  </block>
                </value>
                <value name="B">
                  <shadow type="math_number" id=";(PBMt(9fPe84P0`MRRO">
                    <field name="NUM">1</field>
                  </shadow>
                  <block type="math_number" id=";)+n7kB.._k3n:rt!GvJ">
                    <field name="NUM">100</field>
                  </block>
                </value>
              </block>
            </value>
            <next>
              <block type="controls_if" id="P/L5q|aftSE^KsctnA}E">
                <mutation else="1"></mutation>
                <value name="IF0">
                  <block type="variables_get" id="IE(_]mU,GAeY}*bDjQY@">
                    <field name="VAR">dalembert:resultIsWin</field>
                  </block>
                </value>
                <statement name="DO0">
                  <block type="notify" id="Y+/B?@*,K~?KRM!)/fmK">
                    <field name="NOTIFICATION_TYPE">success</field>
                    <value name="MESSAGE">
                      <block type="text_join" id="4{*#BHVCa/!8W=WM7Kz8">
                        <mutation items="2"></mutation>
                        <value name="ADD0">
                          <block type="text" id="I-e_UTV7xCYiDFI})Q=(">
                            <field name="TEXT">Won:</field>
                          </block>
                        </value>
                        <value name="ADD1">
                          <block type="variables_get" id="k4nklyFK@UB@/FR9Lp|s">
                            <field name="VAR">dalembert:profit</field>
                          </block>
                        </value>
                      </block>
                    </value>
                  </block>
                </statement>
                <statement name="ELSE">
                  <block type="notify" id=",llDyR^DXy%PU^4]}f./">
                    <field name="NOTIFICATION_TYPE">warn</field>
                    <value name="MESSAGE">
                      <block type="text_join" id="/HOAuftQSV1A*1Bigv8-">
                        <mutation items="2"></mutation>
                        <value name="ADD0">
                          <block type="text" id="gF}3UoFAC]sxWV/nw%ei">
                            <field name="TEXT">Lost: </field>
                          </block>
                        </value>
                        <value name="ADD1">
                          <block type="math_single" id="1SW+cz/lMmWY)ms^lqaZ">
                            <field name="OP">ABS</field>
                            <value name="NUM">
                              <shadow type="math_number" id="GleSn`9j7Cm7/dqg}FIA">
                                <field name="NUM">9</field>
                              </shadow>
                              <block type="variables_get" id="`]%tyAnT!{u4,M%!D1bd">
                                <field name="VAR">dalembert:profit</field>
                              </block>
                            </value>
                          </block>
                        </value>
                      </block>
                    </value>
                  </block>
                </statement>
                <next>
                  <block type="procedures_callnoreturn" id="sDq[vcSX3kB!@W09lkSI">
                    <mutation name="D'Alembert Core Functionality">
                      <arg name="dalembert:resultIsWin"></arg>
                    </mutation>
                    <value name="ARG0">
                      <block type="variables_get" id=",gx.@YSp(M2f-koK!twT">
                        <field name="VAR">dalembert:resultIsWin</field>
                      </block>
                    </value>
                    <next>
                      <block type="notify" id="Cvi8%t{p9/_xm#+X]om(">
                        <field name="NOTIFICATION_TYPE">info</field>
                        <value name="MESSAGE">
                          <block type="text_join" id="BJCQ#/4O0}z[^DR9GgkO">
                            <mutation items="2"></mutation>
                            <value name="ADD0">
                              <block type="text" id="ijsv9!fxO*BB:8yHR`f|">
                                <field name="TEXT">Total Profit: </field>
                              </block>
                            </value>
                            <value name="ADD1">
                              <block type="variables_get" id="Kc?RVUrXujr{1X[%y1sW">
                                <field name="VAR">dalembert:totalProfit</field>
                              </block>
                            </value>
                          </block>
                        </value>
                        <next>
                          <block type="variables_set" id="ix3Jwr;,l7NS%LeIjciS">
                            <field name="VAR">dalembert:tradeAgain</field>
                            <value name="VALUE">
                              <block type="logic_boolean" id="Z;.teZof4syfkPW!mqo,">
                                <field name="BOOL">FALSE</field>
                              </block>
                            </value>
                            <next>
                              <block type="controls_if" id="]Kv}Tw=x^zr6@I@D@S4q">
                                <mutation else="1"></mutation>
                                <value name="IF0">
                                  <block type="logic_compare" id=")|LQhZk*#Wi64TgP!Xa^">
                                    <field name="OP">LT</field>
                                    <value name="A">
                                      <block type="variables_get" id="JIN._QaycDvYwCfcJGCM">
                                        <field name="VAR">dalembert:totalProfit</field>
                                      </block>
                                    </value>
                                    <value name="B">
                                      <block type="variables_get" id="ca~g-NW_y(msxA`ID6uw">
                                        <field name="VAR">dalembert:expectedProfit</field>
                                      </block>
                                    </value>
                                  </block>
                                </value>
                                <statement name="DO0">
                                  <block type="controls_if" id="fVNi_Cv-~iB/uc)2U.3u">
                                    <mutation else="1"></mutation>
                                    <value name="IF0">
                                      <block type="logic_compare" id="+`bh%N2o{Y5P*([/ypeU">
                                        <field name="OP">GT</field>
                                        <value name="A">
                                          <block type="variables_get" id="J~+vmLG#*!wX@7rgH_a9">
                                            <field name="VAR">dalembert:totalProfit</field>
                                          </block>
                                        </value>
                                        <value name="B">
                                          <block type="math_single" id="ETDn1dh]F.b#8{zcD@+|">
                                            <field name="OP">NEG</field>
                                            <value name="NUM">
                                              <shadow type="math_number" id="#4N:bIe?FzTA#rOZjMqo">
                                                <field name="NUM">9</field>
                                              </shadow>
                                              <block type="variables_get" id="OovN9^AB=zF:sTh-=oGq">
                                                <field name="VAR">dalembert:maximumLoss</field>
                                              </block>
                                            </value>
                                          </block>
                                        </value>
                                      </block>
                                    </value>
                                    <statement name="DO0">
                                      <block type="variables_set" id="y%eZ%16)YFB?;J!WT-/1">
                                        <field name="VAR">dalembert:tradeAgain</field>
                                        <value name="VALUE">
                                          <block type="logic_boolean" id="qt?z|=[ordjkFsa{CxlK">
                                            <field name="BOOL">TRUE</field>
                                          </block>
                                        </value>
                                      </block>
                                    </statement>
                                    <statement name="ELSE">
                                      <block type="text_print" id="(!.##DU]KjPhy^tQC6YF">
                                        <value name="TEXT">
                                          <shadow type="text" id="kqlrIk.GO.^}hI,PoUV)">
                                            <field name="TEXT">abc</field>
                                          </shadow>
                                          <block type="text_join" id="oX?Ia)5gqDMl[H*da_9g">
                                            <mutation items="2"></mutation>
                                            <value name="ADD0">
                                              <block type="text" id="ox|AU:{^KZm`Bk=piPeZ">
                                                <field name="TEXT">Maximum Loss Occurred! Total Loss: </field>
                                              </block>
                                            </value>
                                            <value name="ADD1">
                                              <block type="math_single" id="bc,1cQ})F_fQN*9Fird^">
                                                <field name="OP">NEG</field>
                                                <value name="NUM">
                                                  <shadow type="math_number" id="pi;;Fh3#fMUD2s`W_UJZ">
                                                    <field name="NUM">9</field>
                                                  </shadow>
                                                  <block type="variables_get" id="=b`joCv5,]G3N=_{)2ND">
                                                    <field name="VAR">dalembert:totalProfit</field>
                                                  </block>
                                                </value>
                                              </block>
                                            </value>
                                          </block>
                                        </value>
                                      </block>
                                    </statement>
                                  </block>
                                </statement>
                                <statement name="ELSE">
                                  <block type="text_print" id="RqQw_^5^@PdBOSiPMkW7">
                                    <value name="TEXT">
                                      <shadow type="text" id="kqlrIk.GO.^}hI,PoUV)">
                                        <field name="TEXT">abc</field>
                                      </shadow>
                                      <block type="text_join" id="uNhAtc%n?rJat;igy.i;">
                                        <mutation items="2"></mutation>
                                        <value name="ADD0">
                                          <block type="text" id="+Fd!Q%aw=bq2)~qEmqt=">
                                            <field name="TEXT">Expected Profit Made! Total Profit: </field>
                                          </block>
                                        </value>
                                        <value name="ADD1">
                                          <block type="variables_get" id="CxB@:}TG^Od;=yysk/#C">
                                            <field name="VAR">dalembert:totalProfit</field>
                                          </block>
                                        </value>
                                      </block>
                                    </value>
                                  </block>
                                </statement>
                              </block>
                            </next>
                          </block>
                        </next>
                      </block>
                    </next>
                  </block>
                </next>
              </block>
            </next>
          </block>
        </next>
      </block>
    </statement>
    <value name="RETURN">
      <block type="variables_get" id="zEXck3l4zHs1m9JF0^g.">
        <field name="VAR">dalembert:tradeAgain</field>
      </block>
    </value>
  </block>
  <block type="procedures_callreturn" id="-Zqm.;O)H:07b;VwRd_?" x="0" y="156">
    <mutation name="D'Alembert Trade Amount"></mutation>
  </block>
  <block type="controls_if" id="=KbO,-HqtVsGwXTFQu;A" x="0" y="206">
    <value name="IF0">
      <block type="procedures_callreturn" id="#:Mg|GlkP@A6U0TvjHaG">
        <mutation name="D'Alembert Trade Again After Purchase">
          <arg name="dalembert:profit"></arg>
          <arg name="dalembert:resultIsWin"></arg>
        </mutation>
        <value name="ARG0">
          <block type="read_details" id="(E,!25pd^Ev`yMmr[z*_" disabled="true">
            <field name="DETAIL_INDEX">4</field>
          </block>
        </value>
        <value name="ARG1">
          <block type="contract_check_result" id="^ShXafO+N,gqVXtl^w)e" disabled="true">
            <field name="CHECK_RESULT">win</field>
          </block>
        </value>
      </block>
    </value>
    <statement name="DO0">
      <block type="trade_again" id="wK(XN;iOhw^@0?^z74gG" disabled="true"></block>
    </statement>
  </block>
</xml>
