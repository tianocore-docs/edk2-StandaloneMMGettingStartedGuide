<!--- @file
  Summary

  Copyright (c) 2025, Intel Corporation. All rights reserved.<BR>

  Redistribution and use in source (original document form) and 'compiled'
  forms (converted to PDF, epub, HTML and other formats) with or without
  modification, are permitted provided that the following conditions are met:

  1) Redistributions of source code (original document form) must retain the
     above copyright notice, this list of conditions and the following
     disclaimer as the first lines of this file unmodified.

  2) Redistributions in compiled form (transformed to other DTDs, converted to
     PDF, epub, HTML and other formats) must reproduce the above copyright
     notice, this list of conditions and the following disclaimer in the
     documentation and/or other materials provided with the distribution.

  THIS DOCUMENTATION IS PROVIDED BY TIANOCORE PROJECT "AS IS" AND ANY EXPRESS OR
  IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF
  MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO
  EVENT SHALL TIANOCORE PROJECT  BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
  SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO,
  PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS;
  OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
  WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
  OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS DOCUMENTATION, EVEN IF
  ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

-->

# Summary

* [Getting Started Guide for Standalone MM on X86 Systems](README.md)

* [1 MM Introduction](1_mm_introduction.md#1-mm-introduction)
  * [1.1 SMM and MM Overview](1_mm_introduction.md#11-smm-and-mm-overview)
  * [1.2 MM Driver Dispatch](1_mm_introduction.md#12-mm-driver-dispatch)
  * [1.3 MM Communication Buffer](1_mm_introduction.md#13-mm-communication-buffer)
  * [1.4 Non-MMRAM Access](1_mm_introduction.md#14-non-mmram-access)
  * [1.5 MM HOBs](1_mm_introduction.md#15-mm-hobs)
    * [1.51 MM Foundation HOBs](1_mm_introduction.md#151-mm-foundation-hobs)
    * [1.52 MM Platform HOBs](1_mm_introduction.md#152-mm-platform-hobs)
  * [1.6 Data Communication between SMM/Non-SMM](1_mm_introduction.md#16-data-communication-between-smmnon-smm)
  * [1.7 Memory Protection](1_mm_introduction.md#17-memory-protection)

* [2 SMM to MM Porting Guide](2_smm_to_mm_porting_guide.md#2-smm-to-mm-porting-guide)
  * [2.1 Porting Design Overview](2_smm_to_mm_porting_guide.md#21-porting-design-overview)
  * [2.2 Checkpoints in Converted MM Driver](2_smm_to_mm_porting_guide.md#22-checkpoints-in-converted-mm-driver)
  * [2.3 Sample: SMM to MM Conversion](2_smm_to_mm_porting_guide.md#23-sample-smm-to-mm-conversion)

---

* Tables
  * [Table 1 - SMM and MM Memory Protection Policy](1_mm_introduction.md#table-1-smm-and-mm-memory-protection-policy)

---

* Figures
 * [Figure 1 - MM Driver Dispatch Flow](1_mm_introduction.md#figure-1-mm-driver-dispatch-flow)
 * [Figure 2 - SMM to MM Conversion](2_smm_to_mm_porting_guide.md#figure-2-smm-to-mm-conversion)
 * [Figure 3 - Tcg2 SMM and MM Module Type](2_smm_to_mm_porting_guide.md#figure-3-tcg2-smm-and-mm-module-type)
 * [Figure 4 - Tcg2 SMM and MM Entry Point](2_smm_to_mm_porting_guide.md#figure-4-tcg2-smm-and-mm-entry-point)
 * [Figure 5 - Tcg2 HOB to Replace PCD](2_smm_to_mm_porting_guide.md#figure-5-tcg2-hob-to-replace-pcd)
 * [Figure 6 - Tcg2 Primary and Non-Primary Buffer Check](2_smm_to_mm_porting_guide.md#figure-6-tcg2-primary-and-non-primary-buffer-check)
