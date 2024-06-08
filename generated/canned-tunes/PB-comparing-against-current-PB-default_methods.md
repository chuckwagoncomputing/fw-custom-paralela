```
static void pbcannedknockNoiseRpmBins() {
	static const float hardCodedknockNoiseRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->knockNoiseRpmBins, hardCodedknockNoiseRpmBins);
}

static void pbcannedknockBaseNoise() {
	static const float hardCodedknockBaseNoise[16] = {-28.0, -28.0, -24.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -17.0, -17.0, -17.0, -17.0, -17.0, -17.0, -17.0};
	copyArray(config->knockBaseNoise, hardCodedknockBaseNoise);
}

static void pbcanneddwellVoltageCorrVoltBins() {
	static const float hardCodeddwellVoltageCorrVoltBins[8] = {8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0};
	copyArray(config->dwellVoltageCorrVoltBins, hardCodeddwellVoltageCorrVoltBins);
}

static void pbcanneddwellVoltageCorrValues() {
	static const float hardCodeddwellVoltageCorrValues[8] = {1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->dwellVoltageCorrValues, hardCodeddwellVoltageCorrValues);
}

static void pbcannedtpsTspCorrValuesBins() {
	static const float hardCodedtpsTspCorrValuesBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->tpsTspCorrValuesBins, hardCodedtpsTspCorrValuesBins);
}

static void pbcannedtpsTspCorrValues() {
	static const float hardCodedtpsTspCorrValues[4] = {1.0, 1.0, 1.0, 1.0};
	copyArray(config->tpsTspCorrValues, hardCodedtpsTspCorrValues);
}

static void pbcannedmafDecodingBins() {
	static const float hardCodedmafDecodingBins[32] = {0.0, 0.78125, 1.3867188, 2.9101562, 4.2578125, 4.9804688, 2016.0, 2017.0, 2018.0, 2019.0, 2020.0, 2021.0, 2022.0, 2023.0, 2024.0, 2025.0, 2026.0, 2027.0, 2028.0, 2029.0, 2030.0, 2031.0, 2032.0, 2033.0, 2034.0, 2035.0, 2036.0, 2037.0, 2038.0, 2039.0, 2040.0, 2041.0};
	copyArray(config->mafDecodingBins, hardCodedmafDecodingBins);
}

static void pbcannedmafDecoding() {
	static const float hardCodedmafDecoding[32] = {-34.5, -6.0, 10.5, 105.3, 387.5, 738.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0};
	copyArray(config->mafDecoding, hardCodedmafDecoding);
}

static void pbcannediatFuelCorrBins() {
	static const float hardCodediatFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->iatFuelCorrBins, hardCodediatFuelCorrBins);
}

static void pbcannediatFuelCorr() {
	static const float hardCodediatFuelCorr[16] = {1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->iatFuelCorr, hardCodediatFuelCorr);
}

static void pbcannedcltTimingBins() {
	static const float hardCodedcltTimingBins[8] = {-40.0, -17.0, 6.0, 30.0, 40.0, 50.0, 97.0, 120.0};
	copyArray(config->cltTimingBins, hardCodedcltTimingBins);
}

static void pbcannedcltTimingExtra() {
	static const float hardCodedcltTimingExtra[8] = {0.0, 0.0, -30.0, -30.0, -30.0, 0.0, 0.0, 0.0};
	copyArray(config->cltTimingExtra, hardCodedcltTimingExtra);
}

static void pbcannedcltFuelCorrBins() {
	static const float hardCodedcltFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->cltFuelCorrBins, hardCodedcltFuelCorrBins);
}

static void pbcannedcltFuelCorr() {
	static const float hardCodedcltFuelCorr[16] = {1.5, 1.5, 1.42, 1.36, 1.28, 1.19, 1.12, 1.1, 1.06, 1.06, 1.03, 1.01, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->cltFuelCorr, hardCodedcltFuelCorr);
}

static void pbcannedcrankingFuelBins() {
	static const float hardCodedcrankingFuelBins[8] = {-20.0, -10.0, 5.0, 20.0, 35.0, 50.0, 65.0, 90.0};
	copyArray(config->crankingFuelBins, hardCodedcrankingFuelBins);
}

static void pbcannedcrankingFuelCoef() {
	static const float hardCodedcrankingFuelCoef[8] = {2.8, 2.2, 1.8, 1.55, 1.3, 1.1, 1.0, 1.0};
	copyArray(config->crankingFuelCoef, hardCodedcrankingFuelCoef);
}

static void pbcannedcrankingFuelCoefE100() {
	static const float hardCodedcrankingFuelCoefE100[8] = {2.8, 2.2, 1.8, 1.55, 1.3, 1.1, 1.0, 1.0};
	copyArray(config->crankingFuelCoefE100, hardCodedcrankingFuelCoefE100);
}

static void pbcannedcltRevLimitRpmBins() {
	static const float hardCodedcltRevLimitRpmBins[4] = {-20.0, 0.0, 40.0, 80.0};
	copyArray(config->cltRevLimitRpmBins, hardCodedcltRevLimitRpmBins);
}

static void pbcannedcltRevLimitRpm() {
	static const float hardCodedcltRevLimitRpm[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->cltRevLimitRpm, hardCodedcltRevLimitRpm);
}

static void pbcannedcltIdleCorrBins() {
	static const float hardCodedcltIdleCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->cltIdleCorrBins, hardCodedcltIdleCorrBins);
}

static void pbcannedcltIdleCorr() {
	static const float hardCodedcltIdleCorr[16] = {1.5, 1.5, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.2, 1.0, 1.0, 1.0, 0.8, 0.8, 0.8, 1.0};
	copyArray(config->cltIdleCorr, hardCodedcltIdleCorr);
}

static void pbcannedcltIdleRpm() {
	static const float hardCodedcltIdleRpm[16] = {1360.0, 1360.0, 1300.0, 1200.0, 1160.0, 1100.0, 1060.0, 1000.0, 1000.0, 960.0, 960.0, 740.0, 740.0, 740.0, 860.0, 1100.0};
	copyArray(config->cltIdleRpm, hardCodedcltIdleRpm);
}

static void pbcannedidleAdvanceBins() {
	static const float hardCodedidleAdvanceBins[8] = {500.0, 650.0, 800.0, 950.0, 1050.0, 1200.0, 1350.0, 1500.0};
	copyArray(config->idleAdvanceBins, hardCodedidleAdvanceBins);
}

static void pbcannedidleAdvance() {
	static const float hardCodedidleAdvance[8] = {12.0, 12.571428, 13.142858, 13.714286, 14.285714, 14.857142, 15.428572, 16.0};
	copyArray(config->idleAdvance, hardCodedidleAdvance);
}

static void pbcannedfuelLevelBins() {
	static const float hardCodedfuelLevelBins[8] = {0.0, 0.71, 1.43, 2.14, 2.86, 3.57, 4.29, 5.0};
	copyArray(config->fuelLevelBins, hardCodedfuelLevelBins);
}

static void pbcannedfuelLevelValues() {
	static const float hardCodedfuelLevelValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelLevelValues, hardCodedfuelLevelValues);
}

static void pbcannedhpfpLobeProfileQuantityBins() {
	static const float hardCodedhpfpLobeProfileQuantityBins[16] = {0.0, 1.0, 4.5, 9.5, 16.5, 25.0, 34.5, 45.0, 55.0, 65.5, 75.0, 83.5, 90.5, 95.5, 99.0, 100.0};
	copyArray(config->hpfpLobeProfileQuantityBins, hardCodedhpfpLobeProfileQuantityBins);
}

static void pbcannedhpfpLobeProfileAngle() {
	static const float hardCodedhpfpLobeProfileAngle[16] = {0.0, 7.5, 16.5, 24.0, 32.0, 40.0, 48.0, 56.0, 64.0, 72.0, 80.0, 88.0, 96.0, 103.5, 112.5, 120.0};
	copyArray(config->hpfpLobeProfileAngle, hardCodedhpfpLobeProfileAngle);
}

static void pbcannedhpfpDeadtimeVoltsBins() {
	static const float hardCodedhpfpDeadtimeVoltsBins[8] = {8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 15.0, 16.0};
	copyArray(config->hpfpDeadtimeVoltsBins, hardCodedhpfpDeadtimeVoltsBins);
}

static void pbcannedwwCltBins() {
	static const float hardCodedwwCltBins[8] = {-40.0, -20.0, 0.0, 20.0, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->wwCltBins, hardCodedwwCltBins);
}

static void pbcannedwwTauCltValues() {
	static const float hardCodedwwTauCltValues[8] = {1.45, 1.3, 1.17, 1.05, 0.9, 0.82, 0.75, 0.7};
	copyArray(config->wwTauCltValues, hardCodedwwTauCltValues);
}

static void pbcannedwwMapBins() {
	static const float hardCodedwwMapBins[8] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0};
	copyArray(config->wwMapBins, hardCodedwwMapBins);
}

static void pbcannedwwTauMapValues() {
	static const float hardCodedwwTauMapValues[8] = {0.38, 0.55, 0.69, 0.86, 0.9, 0.95, 0.97, 1.0};
	copyArray(config->wwTauMapValues, hardCodedwwTauMapValues);
}

static void pbcannedwwBetaCltValues() {
	static const float hardCodedwwBetaCltValues[8] = {0.73, 0.66, 0.57, 0.46, 0.38, 0.31, 0.24, 0.19};
	copyArray(config->wwBetaCltValues, hardCodedwwBetaCltValues);
}

static void pbcannedwwBetaMapValues() {
	static const float hardCodedwwBetaMapValues[8] = {0.21, 0.4, 0.6, 0.79, 0.85, 0.9, 0.95, 1.0};
	copyArray(config->wwBetaMapValues, hardCodedwwBetaMapValues);
}

static void pbcannedtcu_tccTpsBins() {
	static const float hardCodedtcu_tccTpsBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccTpsBins, hardCodedtcu_tccTpsBins);
}

static void pbcannedtcu_tccLockSpeed() {
	static const float hardCodedtcu_tccLockSpeed[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccLockSpeed, hardCodedtcu_tccLockSpeed);
}

static void pbcannedtcu_tccUnlockSpeed() {
	static const float hardCodedtcu_tccUnlockSpeed[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccUnlockSpeed, hardCodedtcu_tccUnlockSpeed);
}

static void pbcannedtcu_pcAirmassBins() {
	static const float hardCodedtcu_pcAirmassBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcAirmassBins, hardCodedtcu_pcAirmassBins);
}

static void pbcannedtcu_pcValsR() {
	static const float hardCodedtcu_pcValsR[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcValsR, hardCodedtcu_pcValsR);
}

static void pbcannedtcu_pcValsN() {
	static const float hardCodedtcu_pcValsN[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcValsN, hardCodedtcu_pcValsN);
}

static void pbcannedtcu_pcVals1() {
	static const float hardCodedtcu_pcVals1[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals1, hardCodedtcu_pcVals1);
}

static void pbcannedtcu_pcVals2() {
	static const float hardCodedtcu_pcVals2[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals2, hardCodedtcu_pcVals2);
}

static void pbcannedtcu_pcVals3() {
	static const float hardCodedtcu_pcVals3[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals3, hardCodedtcu_pcVals3);
}

static void pbcannedtcu_pcVals4() {
	static const float hardCodedtcu_pcVals4[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals4, hardCodedtcu_pcVals4);
}

static void pbcannedtcu_pcVals12() {
	static const float hardCodedtcu_pcVals12[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals12, hardCodedtcu_pcVals12);
}

static void pbcannedtcu_pcVals23() {
	static const float hardCodedtcu_pcVals23[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals23, hardCodedtcu_pcVals23);
}

static void pbcannedtcu_pcVals34() {
	static const float hardCodedtcu_pcVals34[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals34, hardCodedtcu_pcVals34);
}

static void pbcannedtcu_pcVals21() {
	static const float hardCodedtcu_pcVals21[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals21, hardCodedtcu_pcVals21);
}

static void pbcannedtcu_pcVals32() {
	static const float hardCodedtcu_pcVals32[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals32, hardCodedtcu_pcVals32);
}

static void pbcannedtcu_pcVals43() {
	static const float hardCodedtcu_pcVals43[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals43, hardCodedtcu_pcVals43);
}

static void pbcannedtcu_32SpeedBins() {
	static const float hardCodedtcu_32SpeedBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_32SpeedBins, hardCodedtcu_32SpeedBins);
}

static void pbcannedtcu_32Vals() {
	static const float hardCodedtcu_32Vals[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_32Vals, hardCodedtcu_32Vals);
}

static void pbcannedtcu_rangeM() {
	static const float hardCodedtcu_rangeM[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM, hardCodedtcu_rangeM);
}

static void pbcannedtcu_rangeM3() {
	static const float hardCodedtcu_rangeM3[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM3, hardCodedtcu_rangeM3);
}

static void pbcannedtcu_rangeM2() {
	static const float hardCodedtcu_rangeM2[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM2, hardCodedtcu_rangeM2);
}

static void pbcannedtcu_rangeM1() {
	static const float hardCodedtcu_rangeM1[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM1, hardCodedtcu_rangeM1);
}

static void pbcannedignBlends1_blendBins() {
	static const float hardCodedignBlends1_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_blendBins, hardCodedignBlends1_blendBins);
}

static void pbcannedignBlends1_blendValues() {
	static const float hardCodedignBlends1_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_blendValues, hardCodedignBlends1_blendValues);
}

static void pbcannedignBlends2_blendBins() {
	static const float hardCodedignBlends2_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendBins, hardCodedignBlends2_blendBins);
}

static void pbcannedignBlends2_blendValues() {
	static const float hardCodedignBlends2_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendValues, hardCodedignBlends2_blendValues);
}

static void pbcannedignBlends3_blendBins() {
	static const float hardCodedignBlends3_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_blendBins, hardCodedignBlends3_blendBins);
}

static void pbcannedignBlends3_blendValues() {
	static const float hardCodedignBlends3_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_blendValues, hardCodedignBlends3_blendValues);
}

static void pbcannedignBlends4_blendBins() {
	static const float hardCodedignBlends4_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_blendBins, hardCodedignBlends4_blendBins);
}

static void pbcannedignBlends4_blendValues() {
	static const float hardCodedignBlends4_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_blendValues, hardCodedignBlends4_blendValues);
}

static void pbcannedveBlends1_blendBins() {
	static const float hardCodedveBlends1_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_blendBins, hardCodedveBlends1_blendBins);
}

static void pbcannedveBlends1_blendValues() {
	static const float hardCodedveBlends1_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_blendValues, hardCodedveBlends1_blendValues);
}

static void pbcannedveBlends2_blendBins() {
	static const float hardCodedveBlends2_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_blendBins, hardCodedveBlends2_blendBins);
}

static void pbcannedveBlends2_blendValues() {
	static const float hardCodedveBlends2_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_blendValues, hardCodedveBlends2_blendValues);
}

static void pbcannedveBlends3_blendBins() {
	static const float hardCodedveBlends3_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_blendBins, hardCodedveBlends3_blendBins);
}

static void pbcannedveBlends3_blendValues() {
	static const float hardCodedveBlends3_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_blendValues, hardCodedveBlends3_blendValues);
}

static void pbcannedveBlends4_blendBins() {
	static const float hardCodedveBlends4_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendBins, hardCodedveBlends4_blendBins);
}

static void pbcannedveBlends4_blendValues() {
	static const float hardCodedveBlends4_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendValues, hardCodedveBlends4_blendValues);
}

static void pbcannedboostOpenLoopBlends1_blendBins() {
	static const float hardCodedboostOpenLoopBlends1_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostOpenLoopBlends1_blendBins, hardCodedboostOpenLoopBlends1_blendBins);
}

static void pbcannedboostClosedLoopBlends2_blendBins() {
	static const float hardCodedboostClosedLoopBlends2_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_blendBins, hardCodedboostClosedLoopBlends2_blendBins);
}

static void pbcannedthrottleEstimateEffectiveAreaBins() {
	static const float hardCodedthrottleEstimateEffectiveAreaBins[12] = {0.0, 9.1, 18.2, 27.3, 36.4, 45.5, 54.6, 63.6, 72.7, 81.8, 90.9, 100.0};
	copyArray(config->throttleEstimateEffectiveAreaBins, hardCodedthrottleEstimateEffectiveAreaBins);
}

static void pbcannedtpsTpsAccelFromRpmBins() {
	static const float hardCodedtpsTpsAccelFromRpmBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelFromRpmBins, hardCodedtpsTpsAccelFromRpmBins);
}

static void pbcannedtpsTpsAccelToRpmBins() {
	static const float hardCodedtpsTpsAccelToRpmBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelToRpmBins, hardCodedtpsTpsAccelToRpmBins);
}

static void pbcannedtpsTpsAccelTable() {
	static const float hardCodedtpsTpsAccelTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{10.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{17.000,	10.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{23.000,	17.000,	10.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{28.000,	23.000,	17.000,	10.000,	0.000,	0.000,	0.000,	0.000,	},
{32.000,	28.000,	23.000,	17.000,	10.000,	0.000,	0.000,	0.000,	},
{35.000,	32.000,	28.000,	23.000,	17.000,	10.000,	0.000,	0.000,	},
{37.000,	35.000,	32.000,	28.000,	23.000,	17.000,	10.000,	0.000,	},
};
	copyTable(config->tpsTpsAccelTable, hardCodedtpsTpsAccelTable);
}

static void pbcannedtractionControlSlipBins() {
	static const float hardCodedtractionControlSlipBins[6] = {0.8, 0.9, 0.95, 1.05, 1.1, 1.2};
	copyArray(engineConfiguration->tractionControlSlipBins, hardCodedtractionControlSlipBins);
}

static void pbcannedvvtTable1RpmBins() {
	static const float hardCodedvvtTable1RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->vvtTable1RpmBins, hardCodedvvtTable1RpmBins);
}

static void pbcannedvvtTable1LoadBins() {
	static const float hardCodedvvtTable1LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->vvtTable1LoadBins, hardCodedvvtTable1LoadBins);
}

static void pbcannedvvtTable1() {
	static const float hardCodedvvtTable1[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	30.000,	35.000,	35.000,	35.000,	30.000,	20.000,	10.000,	},
{0.000,	30.000,	35.000,	35.000,	35.000,	30.000,	20.000,	10.000,	},
{0.000,	30.000,	35.000,	35.000,	35.000,	30.000,	20.000,	10.000,	},
{0.000,	30.000,	35.000,	35.000,	35.000,	30.000,	20.000,	10.000,	},
};
	copyTable(config->vvtTable1, hardCodedvvtTable1);
}

static void pbcannedvvtTable2RpmBins() {
	static const float hardCodedvvtTable2RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->vvtTable2RpmBins, hardCodedvvtTable2RpmBins);
}

static void pbcannedvvtTable2LoadBins() {
	static const float hardCodedvvtTable2LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->vvtTable2LoadBins, hardCodedvvtTable2LoadBins);
}

static void pbcannedvvtTable2() {
	static const float hardCodedvvtTable2[8][8] = {
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
{45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	45.000,	},
};
	copyTable(config->vvtTable2, hardCodedvvtTable2);
}

static void pbcannedscriptTable1RpmBins() {
	static const float hardCodedscriptTable1RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable1RpmBins, hardCodedscriptTable1RpmBins);
}

static void pbcannedscriptTable1LoadBins() {
	static const float hardCodedscriptTable1LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable1LoadBins, hardCodedscriptTable1LoadBins);
}

static void pbcannedscriptTable2RpmBins() {
	static const float hardCodedscriptTable2RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable2RpmBins, hardCodedscriptTable2RpmBins);
}

static void pbcannedscriptTable2LoadBins() {
	static const float hardCodedscriptTable2LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable2LoadBins, hardCodedscriptTable2LoadBins);
}

static void pbcannedscriptTable3RpmBins() {
	static const float hardCodedscriptTable3RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable3RpmBins, hardCodedscriptTable3RpmBins);
}

static void pbcannedscriptTable3LoadBins() {
	static const float hardCodedscriptTable3LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable3LoadBins, hardCodedscriptTable3LoadBins);
}

static void pbcannedscriptTable3() {
	static const float hardCodedscriptTable3[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->scriptTable3, hardCodedscriptTable3);
}

static void pbcannedscriptTable4RpmBins() {
	static const float hardCodedscriptTable4RpmBins[10] = {650.0, 800.0, 1450.0, 2100.0, 2750.0, 3400.0, 4050.0, 4700.0, 5350.0, 7000.0};
	copyArray(config->scriptTable4RpmBins, hardCodedscriptTable4RpmBins);
}

static void pbcannedscriptTable4LoadBins() {
	static const float hardCodedscriptTable4LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable4LoadBins, hardCodedscriptTable4LoadBins);
}

static void pbcannedscriptTable4() {
	static const float hardCodedscriptTable4[8][10] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->scriptTable4, hardCodedscriptTable4);
}

static void pbcannedalsIgnRetardrpmBins() {
	static const float hardCodedalsIgnRetardrpmBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->alsIgnRetardrpmBins, hardCodedalsIgnRetardrpmBins);
}

static void pbcannedalsIgnRetardLoadBins() {
	static const float hardCodedalsIgnRetardLoadBins[4] = {2.0, 5.0, 7.0, 10.0};
	copyArray(config->alsIgnRetardLoadBins, hardCodedalsIgnRetardLoadBins);
}

static void pbcannedALSTimingRetardTable() {
	static const float hardCodedALSTimingRetardTable[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSTimingRetardTable, hardCodedALSTimingRetardTable);
}

static void pbcannedalsFuelAdjustmentrpmBins() {
	static const float hardCodedalsFuelAdjustmentrpmBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->alsFuelAdjustmentrpmBins, hardCodedalsFuelAdjustmentrpmBins);
}

static void pbcannedalsFuelAdjustmentLoadBins() {
	static const float hardCodedalsFuelAdjustmentLoadBins[4] = {2.0, 5.0, 7.0, 10.0};
	copyArray(config->alsFuelAdjustmentLoadBins, hardCodedalsFuelAdjustmentLoadBins);
}

static void pbcannedALSFuelAdjustment() {
	static const float hardCodedALSFuelAdjustment[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSFuelAdjustment, hardCodedALSFuelAdjustment);
}

static void pbcannedalsIgnSkiprpmBins() {
	static const float hardCodedalsIgnSkiprpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->alsIgnSkiprpmBins, hardCodedalsIgnSkiprpmBins);
}

static void pbcannedalsIgnSkipLoadBins() {
	static const float hardCodedalsIgnSkipLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->alsIgnSkipLoadBins, hardCodedalsIgnSkipLoadBins);
}

static void pbcannedALSIgnSkipTable() {
	static const float hardCodedALSIgnSkipTable[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSIgnSkipTable, hardCodedALSIgnSkipTable);
}

static void pbcannedignitionRpmBins() {
	static const float hardCodedignitionRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 2000.0, 2500.0, 3000.0, 3500.0, 4000.0, 4500.0, 5000.0, 5500.0, 6000.0, 6500.0, 7000.0, 7500.0};
	copyArray(config->ignitionRpmBins, hardCodedignitionRpmBins);
}

static void pbcannedignitionLoadBins() {
	static const float hardCodedignitionLoadBins[16] = {21.0, 27.0, 33.0, 39.0, 48.0, 54.0, 60.0, 66.0, 72.0, 81.0, 87.0, 93.0, 99.0, 108.0, 114.0, 120.0};
	copyArray(config->ignitionLoadBins, hardCodedignitionLoadBins);
}

static void pbcannedignitionTable() {
	static const float hardCodedignitionTable[16][16] = {
{12.200,	14.200,	0.000,	0.000,	36.400,	39.700,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	},
{12.100,	14.000,	0.000,	0.000,	35.600,	39.500,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	-10.000,	},
{11.800,	13.700,	10.000,	14.900,	34.800,	39.200,	39.500,	39.500,	40.500,	41.000,	41.000,	41.000,	41.000,	41.000,	41.000,	41.000,	},
{11.600,	13.400,	12.300,	17.100,	33.900,	39.000,	39.300,	39.300,	39.800,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	},
{14.400,	11.500,	12.100,	16.500,	28.100,	33.700,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	},
{10.200,	10.300,	11.900,	16.000,	27.600,	31.800,	32.600,	32.900,	33.100,	33.300,	33.400,	33.400,	33.400,	33.400,	33.400,	33.400,	},
{9.900,	9.000,	11.800,	15.600,	25.000,	27.800,	29.300,	29.700,	30.100,	30.600,	30.700,	30.700,	30.700,	30.700,	30.700,	30.700,	},
{6.100,	7.800,	11.600,	15.200,	21.500,	22.800,	24.900,	25.600,	26.200,	26.800,	27.100,	27.100,	27.100,	27.100,	27.100,	27.100,	},
{4.100,	5.700,	9.300,	12.600,	18.500,	19.800,	21.900,	22.600,	23.200,	23.800,	24.100,	24.100,	24.100,	24.100,	24.100,	24.100,	},
{2.200,	3.500,	6.900,	10.100,	15.600,	16.900,	19.000,	19.700,	20.300,	20.900,	21.200,	21.200,	21.200,	21.200,	21.200,	21.200,	},
{0.200,	1.400,	4.500,	7.500,	12.600,	13.900,	16.000,	16.700,	17.300,	17.900,	18.200,	18.200,	18.200,	18.200,	18.200,	18.200,	},
{-1.800,	-0.700,	2.100,	5.000,	9.600,	10.900,	13.000,	13.700,	14.300,	14.900,	15.200,	15.200,	15.200,	15.200,	15.200,	15.200,	},
{-3.800,	-2.800,	-0.300,	2.400,	6.600,	7.900,	10.000,	10.700,	11.300,	11.900,	12.200,	12.200,	12.200,	12.200,	12.200,	12.200,	},
{-5.000,	-4.900,	-2.700,	-0.100,	3.700,	5.000,	7.100,	7.800,	8.400,	9.000,	9.300,	9.300,	9.300,	9.300,	9.300,	9.300,	},
{-5.000,	-5.000,	-5.000,	-2.700,	0.700,	2.000,	4.100,	4.800,	5.400,	6.000,	6.300,	6.300,	6.300,	6.300,	6.300,	6.300,	},
{-5.000,	-5.000,	-5.000,	-5.000,	-2.000,	-1.300,	-0.500,	0.100,	0.800,	1.500,	2.000,	2.000,	2.000,	2.000,	2.000,	2.000,	},
};
	copyTable(config->ignitionTable, hardCodedignitionTable);
}

static void pbcannedignBlends1_rpmBins() {
	static const float hardCodedignBlends1_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_rpmBins, hardCodedignBlends1_rpmBins);
}

static void pbcannedignBlends1_loadBins() {
	static const float hardCodedignBlends1_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_loadBins, hardCodedignBlends1_loadBins);
}

static void pbcannedignBlends1_table() {
	static const float hardCodedignBlends1_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.ignBlends1_table, hardCodedignBlends1_table);
}

static void pbcannedignBlends2_rpmBins() {
	static const float hardCodedignBlends2_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_rpmBins, hardCodedignBlends2_rpmBins);
}

static void pbcannedignBlends2_loadBins() {
	static const float hardCodedignBlends2_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_loadBins, hardCodedignBlends2_loadBins);
}

static void pbcannedignBlends2_table() {
	static const float hardCodedignBlends2_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.ignBlends2_table, hardCodedignBlends2_table);
}

static void pbcannedignBlends3_rpmBins() {
	static const float hardCodedignBlends3_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_rpmBins, hardCodedignBlends3_rpmBins);
}

static void pbcannedignBlends3_loadBins() {
	static const float hardCodedignBlends3_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_loadBins, hardCodedignBlends3_loadBins);
}

static void pbcannedignBlends3_table() {
	static const float hardCodedignBlends3_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.ignBlends3_table, hardCodedignBlends3_table);
}

static void pbcannedignBlends4_rpmBins() {
	static const float hardCodedignBlends4_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_rpmBins, hardCodedignBlends4_rpmBins);
}

static void pbcannedignBlends4_loadBins() {
	static const float hardCodedignBlends4_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_loadBins, hardCodedignBlends4_loadBins);
}

static void pbcannedveBlends1_rpmBins() {
	static const float hardCodedveBlends1_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_rpmBins, hardCodedveBlends1_rpmBins);
}

static void pbcannedveBlends1_loadBins() {
	static const float hardCodedveBlends1_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_loadBins, hardCodedveBlends1_loadBins);
}

static void pbcannedveBlends1_table() {
	static const float hardCodedveBlends1_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.veBlends1_table, hardCodedveBlends1_table);
}

static void pbcannedveBlends2_rpmBins() {
	static const float hardCodedveBlends2_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_rpmBins, hardCodedveBlends2_rpmBins);
}

static void pbcannedveBlends2_loadBins() {
	static const float hardCodedveBlends2_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_loadBins, hardCodedveBlends2_loadBins);
}

static void pbcannedveBlends2_table() {
	static const float hardCodedveBlends2_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.veBlends2_table, hardCodedveBlends2_table);
}

static void pbcannedveBlends3_rpmBins() {
	static const float hardCodedveBlends3_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_rpmBins, hardCodedveBlends3_rpmBins);
}

static void pbcannedveBlends3_loadBins() {
	static const float hardCodedveBlends3_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_loadBins, hardCodedveBlends3_loadBins);
}

static void pbcannedveBlends3_table() {
	static const float hardCodedveBlends3_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.veBlends3_table, hardCodedveBlends3_table);
}

static void pbcannedveBlends4_rpmBins() {
	static const float hardCodedveBlends4_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_rpmBins, hardCodedveBlends4_rpmBins);
}

static void pbcannedveBlends4_loadBins() {
	static const float hardCodedveBlends4_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_loadBins, hardCodedveBlends4_loadBins);
}

static void pbcannedboostOpenLoopBlends1_rpmBins() {
	static const float hardCodedboostOpenLoopBlends1_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostOpenLoopBlends1_rpmBins, hardCodedboostOpenLoopBlends1_rpmBins);
}

static void pbcannedboostClosedLoopBlends1_table() {
	static const float hardCodedboostClosedLoopBlends1_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends1_table, hardCodedboostClosedLoopBlends1_table);
}

static void pbcannedboostClosedLoopBlends2_rpmBins() {
	static const float hardCodedboostClosedLoopBlends2_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_rpmBins, hardCodedboostClosedLoopBlends2_rpmBins);
}

static void pbcannedboostClosedLoopBlends2_loadBins() {
	static const float hardCodedboostClosedLoopBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_loadBins, hardCodedboostClosedLoopBlends2_loadBins);
}

static void pbcannedboostClosedLoopBlends2_table() {
	static const float hardCodedboostClosedLoopBlends2_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_table, hardCodedboostClosedLoopBlends2_table);
}

static void pbcannedignitionIatCorrTempBins() {
	static const float hardCodedignitionIatCorrTempBins[8] = {-40.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0};
	copyArray(config->ignitionIatCorrTempBins, hardCodedignitionIatCorrTempBins);
}

static void pbcannedignitionIatCorrLoadBins() {
	static const float hardCodedignitionIatCorrLoadBins[8] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0, 120.0, 140.0};
	copyArray(config->ignitionIatCorrLoadBins, hardCodedignitionIatCorrLoadBins);
}

static void pbcannedignitionIatCorrTable() {
	static const float hardCodedignitionIatCorrTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	-1.000,	-2.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	-1.000,	-2.000,	-3.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	-1.000,	-2.000,	-3.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	-1.000,	-2.000,	-3.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	-1.000,	-2.000,	-3.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	-1.000,	-2.000,	-3.000,	},
};
	copyTable(config->ignitionIatCorrTable, hardCodedignitionIatCorrTable);
}

static void pbcannedveRpmBins() {
	static const float hardCodedveRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->veRpmBins, hardCodedveRpmBins);
}

static void pbcannedveLoadBins() {
	static const float hardCodedveLoadBins[16] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 140.0, 150.0, 160.0};
	copyArray(config->veLoadBins, hardCodedveLoadBins);
}

static void pbcannedveTable() {
	static const float hardCodedveTable[16][16] = {
{50.300,	50.300,	50.400,	50.500,	50.600,	50.600,	50.300,	29.900,	29.800,	29.900,	30.400,	31.400,	33.000,	35.100,	37.700,	40.900,	},
{55.800,	56.500,	57.100,	57.900,	53.300,	52.800,	52.000,	31.300,	31.200,	31.500,	32.200,	33.500,	35.300,	37.700,	40.500,	43.900,	},
{66.700,	67.900,	69.000,	69.900,	74.900,	74.000,	73.000,	82.300,	82.100,	82.400,	83.200,	84.500,	86.300,	88.700,	91.600,	95.000,	},
{70.100,	72.400,	73.500,	73.600,	77.700,	76.200,	75.000,	84.100,	84.000,	84.200,	85.100,	86.400,	88.300,	90.700,	93.600,	97.100,	},
{80.400,	82.100,	82.300,	81.500,	79.900,	78.200,	76.900,	86.400,	86.200,	86.500,	87.400,	88.700,	90.600,	93.000,	96.000,	99.500,	},
{85.000,	85.500,	85.000,	83.700,	86.000,	88.200,	90.400,	89.600,	89.500,	89.700,	90.600,	91.000,	92.900,	95.300,	98.400,	101.900,	},
{88.500,	88.200,	87.300,	85.800,	89.300,	90.200,	92.900,	91.900,	91.700,	92.000,	92.900,	93.200,	95.200,	97.700,	100.700,	104.300,	},
{86.200,	85.400,	84.300,	82.700,	92.500,	92.300,	95.400,	94.100,	94.000,	94.200,	95.100,	95.500,	97.500,	100.000,	103.100,	106.700,	},
{105.600,	104.600,	103.400,	101.700,	95.800,	94.300,	97.900,	96.400,	96.200,	96.500,	97.400,	102.800,	99.800,	102.300,	105.500,	109.100,	},
{113.400,	112.100,	110.800,	109.000,	106.900,	104.800,	103.300,	102.300,	102.100,	102.400,	103.300,	104.800,	106.900,	109.600,	112.900,	116.800,	},
{121.400,	120.000,	118.600,	116.600,	114.400,	112.200,	110.600,	109.500,	109.300,	109.600,	110.600,	112.200,	114.400,	117.300,	120.800,	124.900,	},
{127.600,	126.500,	125.100,	123.000,	120.700,	118.300,	116.600,	115.500,	115.300,	115.600,	116.600,	118.300,	120.700,	123.700,	127.400,	127.600,	},
{127.600,	127.600,	127.600,	127.600,	125.700,	123.300,	121.500,	120.400,	120.100,	120.500,	121.500,	123.300,	125.700,	127.600,	127.600,	127.600,	},
{127.600,	127.600,	127.600,	127.600,	127.600,	127.000,	125.200,	124.000,	123.800,	124.200,	125.200,	127.000,	127.600,	127.600,	127.600,	127.600,	},
{127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	126.500,	126.300,	126.700,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	},
{127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	127.600,	},
};
	copyTable(config->veTable, hardCodedveTable);
}

static void pbcannedfuelTrimRpmBins() {
	static const float hardCodedfuelTrimRpmBins[4] = {1000.0, 3000.0, 5000.0, 7000.0};
	copyArray(config->fuelTrimRpmBins, hardCodedfuelTrimRpmBins);
}

static void pbcannedfuelTrimLoadBins() {
	static const float hardCodedfuelTrimLoadBins[4] = {20.0, 50.0, 80.0, 100.0};
	copyArray(config->fuelTrimLoadBins, hardCodedfuelTrimLoadBins);
}

static void pbcannedfuelTrims1_table() {
	static const float hardCodedfuelTrims1_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims1_table, hardCodedfuelTrims1_table);
}

static void pbcannedfuelTrims2_table() {
	static const float hardCodedfuelTrims2_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims2_table, hardCodedfuelTrims2_table);
}

static void pbcannedfuelTrims3_table() {
	static const float hardCodedfuelTrims3_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims3_table, hardCodedfuelTrims3_table);
}

static void pbcannedfuelTrims4_table() {
	static const float hardCodedfuelTrims4_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims4_table, hardCodedfuelTrims4_table);
}

static void pbcannedfuelTrims5_table() {
	static const float hardCodedfuelTrims5_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims5_table, hardCodedfuelTrims5_table);
}

static void pbcannedfuelTrims6_table() {
	static const float hardCodedfuelTrims6_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims6_table, hardCodedfuelTrims6_table);
}

static void pbcannedfuelTrims7_table() {
	static const float hardCodedfuelTrims7_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims7_table, hardCodedfuelTrims7_table);
}

static void pbcannedfuelTrims8_table() {
	static const float hardCodedfuelTrims8_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims8_table, hardCodedfuelTrims8_table);
}

static void pbcannedfuelTrims9_table() {
	static const float hardCodedfuelTrims9_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims9_table, hardCodedfuelTrims9_table);
}

static void pbcannedfuelTrims10_table() {
	static const float hardCodedfuelTrims10_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims10_table, hardCodedfuelTrims10_table);
}

static void pbcannedfuelTrims11_table() {
	static const float hardCodedfuelTrims11_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims11_table, hardCodedfuelTrims11_table);
}

static void pbcannedfuelTrims12_table() {
	static const float hardCodedfuelTrims12_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims12_table, hardCodedfuelTrims12_table);
}

static void pbcannedignTrimRpmBins() {
	static const float hardCodedignTrimRpmBins[4] = {1000.0, 3000.0, 5000.0, 7000.0};
	copyArray(config->ignTrimRpmBins, hardCodedignTrimRpmBins);
}

static void pbcannedignTrimLoadBins() {
	static const float hardCodedignTrimLoadBins[4] = {20.0, 50.0, 80.0, 100.0};
	copyArray(config->ignTrimLoadBins, hardCodedignTrimLoadBins);
}

static void pbcannedignTrims1_table() {
	static const float hardCodedignTrims1_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims1_table, hardCodedignTrims1_table);
}

static void pbcannedignTrims2_table() {
	static const float hardCodedignTrims2_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims2_table, hardCodedignTrims2_table);
}

static void pbcannedignTrims3_table() {
	static const float hardCodedignTrims3_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims3_table, hardCodedignTrims3_table);
}

static void pbcannedignTrims4_table() {
	static const float hardCodedignTrims4_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims4_table, hardCodedignTrims4_table);
}

static void pbcannedignTrims5_table() {
	static const float hardCodedignTrims5_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims5_table, hardCodedignTrims5_table);
}

static void pbcannedignTrims6_table() {
	static const float hardCodedignTrims6_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims6_table, hardCodedignTrims6_table);
}

static void pbcannedignTrims7_table() {
	static const float hardCodedignTrims7_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims7_table, hardCodedignTrims7_table);
}

static void pbcannedignTrims8_table() {
	static const float hardCodedignTrims8_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims8_table, hardCodedignTrims8_table);
}

static void pbcannedignTrims9_table() {
	static const float hardCodedignTrims9_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims9_table, hardCodedignTrims9_table);
}

static void pbcannedignTrims10_table() {
	static const float hardCodedignTrims10_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims10_table, hardCodedignTrims10_table);
}

static void pbcannedignTrims11_table() {
	static const float hardCodedignTrims11_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims11_table, hardCodedignTrims11_table);
}

static void pbcannedignTrims12_table() {
	static const float hardCodedignTrims12_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims12_table, hardCodedignTrims12_table);
}

static void pbcannedmapEstimateRpmBins() {
	static const float hardCodedmapEstimateRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->mapEstimateRpmBins, hardCodedmapEstimateRpmBins);
}

static void pbcannedmapEstimateTpsBins() {
	static const float hardCodedmapEstimateTpsBins[16] = {0.0, 6.67, 13.33, 20.0, 26.67, 33.33, 40.0, 46.67, 53.33, 60.0, 66.67, 73.33, 80.0, 86.67, 93.33, 100.0};
	copyArray(config->mapEstimateTpsBins, hardCodedmapEstimateTpsBins);
}

static void pbcannedmapEstimateTable() {
	static const float hardCodedmapEstimateTable[16][16] = {
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
};
	copyTable(config->mapEstimateTable, hardCodedmapEstimateTable);
}

static void pbcannedinjPhaseRpmBins() {
	static const float hardCodedinjPhaseRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->injPhaseRpmBins, hardCodedinjPhaseRpmBins);
}

static void pbcannedinjPhaseLoadBins() {
	static const float hardCodedinjPhaseLoadBins[16] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 140.0, 150.0, 160.0};
	copyArray(config->injPhaseLoadBins, hardCodedinjPhaseLoadBins);
}

static void pbcannedinjectionPhase() {
	static const float hardCodedinjectionPhase[16][16] = {
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-250.000,	-240.000,	-240.000,	-240.000,	-240.000,	-240.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-250.000,	-240.000,	-240.000,	-240.000,	-240.000,	-240.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-250.000,	-240.000,	-240.000,	-240.000,	-240.000,	-240.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-250.000,	-240.000,	-240.000,	-240.000,	-240.000,	-240.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-250.000,	-240.000,	-240.000,	-240.000,	-240.000,	-240.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-200.000,	-200.000,	-200.000,	-200.000,	-200.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-180.000,	-180.000,	-180.000,	-180.000,	-180.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-180.000,	-180.000,	-180.000,	-180.000,	-180.000,	},
{-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-220.000,	-250.000,	-250.000,	-230.000,	-180.000,	-180.000,	-180.000,	-180.000,	-180.000,	},
};
	copyTable(config->injectionPhase, hardCodedinjectionPhase);
}

static void pbcannedthrottle2TrimRpmBins() {
	static const float hardCodedthrottle2TrimRpmBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->throttle2TrimRpmBins, hardCodedthrottle2TrimRpmBins);
}

static void pbcannedthrottle2TrimTpsBins() {
	static const float hardCodedthrottle2TrimTpsBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->throttle2TrimTpsBins, hardCodedthrottle2TrimTpsBins);
}

static void pbcannedthrottle2TrimTable() {
	static const float hardCodedthrottle2TrimTable[6][6] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->throttle2TrimTable, hardCodedthrottle2TrimTable);
}

static void pbcannedmaxKnockRetardRpmBins() {
	static const float hardCodedmaxKnockRetardRpmBins[6] = {1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 7000.0};
	copyArray(config->maxKnockRetardRpmBins, hardCodedmaxKnockRetardRpmBins);
}

static void pbcannedmaxKnockRetardLoadBins() {
	static const float hardCodedmaxKnockRetardLoadBins[6] = {20.0, 40.0, 50.0, 60.0, 80.0, 100.0};
	copyArray(config->maxKnockRetardLoadBins, hardCodedmaxKnockRetardLoadBins);
}

static void pbcannedmaxKnockRetardTable() {
	static const float hardCodedmaxKnockRetardTable[6][6] = {
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
};
	copyTable(config->maxKnockRetardTable, hardCodedmaxKnockRetardTable);
}

static void pbcannedlambdaRpmBins() {
	static const float hardCodedlambdaRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->lambdaRpmBins, hardCodedlambdaRpmBins);
}

static void pbcannedlambdaLoadBins() {
	static const float hardCodedlambdaLoadBins[16] = {30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 150.0, 175.0, 200.0, 225.0, 250.0};
	copyArray(config->lambdaLoadBins, hardCodedlambdaLoadBins);
}

static void pbcannedlambdaTable() {
	static const float hardCodedlambdaTable[16][16] = {
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	},
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	},
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	},
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	},
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	},
{14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	},
{13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	13.500,	},
{13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	13.200,	},
{13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	13.100,	},
{12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	12.900,	},
{12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	12.600,	},
{12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	12.300,	},
{11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	11.800,	},
{11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	11.300,	},
{11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	11.000,	},
{10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	10.700,	},
};
	copyTable(config->lambdaTable, hardCodedlambdaTable);
}

static void pbcannedinjectorStagingRpmBins() {
	static const float hardCodedinjectorStagingRpmBins[6] = {650.0, 800.0, 2200.0, 3600.0, 5000.0, 7000.0};
	copyArray(config->injectorStagingRpmBins, hardCodedinjectorStagingRpmBins);
}

static void pbcannedinjectorStagingLoadBins() {
	static const float hardCodedinjectorStagingLoadBins[6] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->injectorStagingLoadBins, hardCodedinjectorStagingLoadBins);
}

static void pbcannedinjectorStagingTable() {
	static const float hardCodedinjectorStagingTable[6][6] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->injectorStagingTable, hardCodedinjectorStagingTable);
}

static void pbcannedhpfpTargetRpmBins() {
	static const float hardCodedhpfpTargetRpmBins[10] = {650.0, 800.0, 1450.0, 2100.0, 2750.0, 3400.0, 4050.0, 4700.0, 5350.0, 7000.0};
	copyArray(config->hpfpTargetRpmBins, hardCodedhpfpTargetRpmBins);
}

static void pbcannedhpfpTargetLoadBins() {
	static const float hardCodedhpfpTargetLoadBins[10] = {20.0, 40.0, 50.0, 60.0, 80.0, 100.0, 120.0, 140.0, 160.0, 180.0};
	copyArray(config->hpfpTargetLoadBins, hardCodedhpfpTargetLoadBins);
}

static void pbcannedhpfpCompensationRpmBins() {
	static const float hardCodedhpfpCompensationRpmBins[10] = {650.0, 800.0, 1450.0, 2100.0, 2750.0, 3400.0, 4050.0, 4700.0, 5350.0, 7000.0};
	copyArray(config->hpfpCompensationRpmBins, hardCodedhpfpCompensationRpmBins);
}

static void pbcannedhpfpCompensationLoadBins() {
	static const float hardCodedhpfpCompensationLoadBins[10] = {0.005, 0.018, 0.031, 0.043, 0.056, 0.069, 0.082, 0.094, 0.107, 0.12};
	copyArray(config->hpfpCompensationLoadBins, hardCodedhpfpCompensationLoadBins);
}

static void pbcannedhpfpCompensation() {
	static const float hardCodedhpfpCompensation[10][10] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->hpfpCompensation, hardCodedhpfpCompensation);
}

static void pbcannedcrankingCycleBins() {
	static const float hardCodedcrankingCycleBins[8] = {1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0};
	copyArray(config->crankingCycleBins, hardCodedcrankingCycleBins);
}

```
