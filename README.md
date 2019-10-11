# VHDL_and_SV_formal_grammar_to_ANTLR4
Convert PDF with grammar of IEEE1076-2008 and IEEE1800-2017 to ANTLR4 grammar

Junkyard for scripts used to extract and optimalize SystemVerilog and VHDL grammars for [hdlConvertor](https://github.com/Nic30/hdlConvertor)

## What is actually inside?

* antlr4/
  * object for representation of antlr4 grammars, analysis tools and tranformations to optimize it
* rest is related to a SV or VHDL first part extract a formal grammar from PDF to some raw grammar (called proto_grammar)
  This grammar is then parsed by main grammar generator and it is translated to more optimal form.
