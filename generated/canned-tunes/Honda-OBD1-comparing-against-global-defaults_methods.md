```
static void cannedknockNoiseRpmBins() {
	static const float hardCodedknockNoiseRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->knockNoiseRpmBins, hardCodedknockNoiseRpmBins);
}

static void cannedknockBaseNoise() {
	static const float hardCodedknockBaseNoise[16] = {-20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0};
	copyArray(config->knockBaseNoise, hardCodedknockBaseNoise);
}

static void canneddwellVoltageCorrVoltBins() {
	static const float hardCodeddwellVoltageCorrVoltBins[8] = {8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0};
	copyArray(config->dwellVoltageCorrVoltBins, hardCodeddwellVoltageCorrVoltBins);
}

static void canneddwellVoltageCorrValues() {
	static const float hardCodeddwellVoltageCorrValues[8] = {1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->dwellVoltageCorrValues, hardCodeddwellVoltageCorrValues);
}

static void cannedtpsTspCorrValuesBins() {
	static const float hardCodedtpsTspCorrValuesBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->tpsTspCorrValuesBins, hardCodedtpsTspCorrValuesBins);
}

static void cannedtpsTspCorrValues() {
	static const float hardCodedtpsTspCorrValues[4] = {1.0, 1.0, 1.0, 1.0};
	copyArray(config->tpsTspCorrValues, hardCodedtpsTspCorrValues);
}

static void cannedinjector_battLagCorrBins() {
	static const float hardCodedinjector_battLagCorrBins[8] = {0.0, 6.0, 8.0, 9.92, 12.05, 13.15, 14.16, 16.0};
	copyArray(engineConfiguration->injectorSecondary.injector_battLagCorrBins, hardCodedinjector_battLagCorrBins);
}

static void cannedinjector_battLagCorr() {
	static const float hardCodedinjector_battLagCorr[8] = {3.37, 2.04, 1.53, 1.09, 0.62, 0.51, 0.47, 0.33};
	copyArray(engineConfiguration->injectorSecondary.injector_battLagCorr, hardCodedinjector_battLagCorr);
}

static void cannedmafDecodingBins() {
	static const float hardCodedmafDecodingBins[32] = {0.0, 0.78125, 1.3867188, 2.9101562, 4.2578125, 4.9804688, 2016.0, 2017.0, 2018.0, 2019.0, 2020.0, 2021.0, 2022.0, 2023.0, 2024.0, 2025.0, 2026.0, 2027.0, 2028.0, 2029.0, 2030.0, 2031.0, 2032.0, 2033.0, 2034.0, 2035.0, 2036.0, 2037.0, 2038.0, 2039.0, 2040.0, 2041.0};
	copyArray(config->mafDecodingBins, hardCodedmafDecodingBins);
}

static void cannedmafDecoding() {
	static const float hardCodedmafDecoding[32] = {-34.5, -6.0, 10.5, 105.3, 387.5, 738.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0};
	copyArray(config->mafDecoding, hardCodedmafDecoding);
}

static void cannediatFuelCorrBins() {
	static const float hardCodediatFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->iatFuelCorrBins, hardCodediatFuelCorrBins);
}

static void cannediatFuelCorr() {
	static const float hardCodediatFuelCorr[16] = {1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->iatFuelCorr, hardCodediatFuelCorr);
}

static void cannedcltFuelCorrBins() {
	static const float hardCodedcltFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->cltFuelCorrBins, hardCodedcltFuelCorrBins);
}

static void cannedcltFuelCorr() {
	static const float hardCodedcltFuelCorr[16] = {1.5, 1.5, 1.42, 1.36, 1.28, 1.19, 1.12, 1.1, 1.06, 1.06, 1.03, 1.01, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->cltFuelCorr, hardCodedcltFuelCorr);
}

static void cannedcrankingFuelBins() {
	static const float hardCodedcrankingFuelBins[8] = {-20.0, -10.0, 5.0, 20.0, 35.0, 50.0, 65.0, 90.0};
	copyArray(config->crankingFuelBins, hardCodedcrankingFuelBins);
}

static void cannedcrankingFuelCoef() {
	static const float hardCodedcrankingFuelCoef[8] = {2.8, 2.2, 1.8, 1.55, 1.3, 1.1, 1.0, 1.0};
	copyArray(config->crankingFuelCoef, hardCodedcrankingFuelCoef);
}

static void cannedcrankingFuelCoefE100() {
	static const float hardCodedcrankingFuelCoefE100[8] = {2.8, 2.2, 1.8, 1.55, 1.3, 1.1, 1.0, 1.0};
	copyArray(config->crankingFuelCoefE100, hardCodedcrankingFuelCoefE100);
}

static void cannedcltRevLimitRpmBins() {
	static const float hardCodedcltRevLimitRpmBins[4] = {-20.0, 0.0, 40.0, 80.0};
	copyArray(config->cltRevLimitRpmBins, hardCodedcltRevLimitRpmBins);
}

static void cannedcltRevLimitRpm() {
	static const float hardCodedcltRevLimitRpm[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->cltRevLimitRpm, hardCodedcltRevLimitRpm);
}

static void cannedcrankingCycleBins() {
	static const float hardCodedcrankingCycleBins[8] = {1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0};
	copyArray(config->crankingCycleBins, hardCodedcrankingCycleBins);
}

static void cannedcrankingCycleCoef() {
	static const float hardCodedcrankingCycleCoef[8] = {2.0, 1.3, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->crankingCycleCoef, hardCodedcrankingCycleCoef);
}

static void cannedcltIdleCorrBins() {
	static const float hardCodedcltIdleCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->cltIdleCorrBins, hardCodedcltIdleCorrBins);
}

static void cannedcltIdleCorr() {
	static const float hardCodedcltIdleCorr[16] = {1.5, 1.5, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.3333334, 1.2333333, 1.1666666, 1.1, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->cltIdleCorr, hardCodedcltIdleCorr);
}

static void cannedfuelLevelBins() {
	static const float hardCodedfuelLevelBins[8] = {0.0, 0.71, 1.43, 2.14, 2.86, 3.57, 4.29, 5.0};
	copyArray(config->fuelLevelBins, hardCodedfuelLevelBins);
}

static void cannedfuelLevelValues() {
	static const float hardCodedfuelLevelValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelLevelValues, hardCodedfuelLevelValues);
}

static void cannedhpfpLobeProfileQuantityBins() {
	static const float hardCodedhpfpLobeProfileQuantityBins[16] = {0.0, 1.0, 4.5, 9.5, 16.5, 25.0, 34.5, 45.0, 55.0, 65.5, 75.0, 83.5, 90.5, 95.5, 99.0, 100.0};
	copyArray(config->hpfpLobeProfileQuantityBins, hardCodedhpfpLobeProfileQuantityBins);
}

static void cannedhpfpLobeProfileAngle() {
	static const float hardCodedhpfpLobeProfileAngle[16] = {0.0, 7.5, 16.5, 24.0, 32.0, 40.0, 48.0, 56.0, 64.0, 72.0, 80.0, 88.0, 96.0, 103.5, 112.5, 120.0};
	copyArray(config->hpfpLobeProfileAngle, hardCodedhpfpLobeProfileAngle);
}

static void cannedhpfpDeadtimeVoltsBins() {
	static const float hardCodedhpfpDeadtimeVoltsBins[8] = {8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 15.0, 16.0};
	copyArray(config->hpfpDeadtimeVoltsBins, hardCodedhpfpDeadtimeVoltsBins);
}

static void cannedwwCltBins() {
	static const float hardCodedwwCltBins[8] = {-40.0, -20.0, 0.0, 20.0, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->wwCltBins, hardCodedwwCltBins);
}

static void cannedwwTauCltValues() {
	static const float hardCodedwwTauCltValues[8] = {1.45, 1.3, 1.17, 1.05, 0.9, 0.82, 0.75, 0.7};
	copyArray(config->wwTauCltValues, hardCodedwwTauCltValues);
}

static void cannedwwMapBins() {
	static const float hardCodedwwMapBins[8] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0};
	copyArray(config->wwMapBins, hardCodedwwMapBins);
}

static void cannedwwTauMapValues() {
	static const float hardCodedwwTauMapValues[8] = {0.38, 0.55, 0.69, 0.86, 0.9, 0.95, 0.97, 1.0};
	copyArray(config->wwTauMapValues, hardCodedwwTauMapValues);
}

static void cannedwwBetaCltValues() {
	static const float hardCodedwwBetaCltValues[8] = {0.73, 0.66, 0.57, 0.46, 0.38, 0.31, 0.24, 0.19};
	copyArray(config->wwBetaCltValues, hardCodedwwBetaCltValues);
}

static void cannedwwBetaMapValues() {
	static const float hardCodedwwBetaMapValues[8] = {0.21, 0.4, 0.6, 0.79, 0.85, 0.9, 0.95, 1.0};
	copyArray(config->wwBetaMapValues, hardCodedwwBetaMapValues);
}

static void cannedtcu_tccTpsBins() {
	static const float hardCodedtcu_tccTpsBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccTpsBins, hardCodedtcu_tccTpsBins);
}

static void cannedtcu_tccLockSpeed() {
	static const float hardCodedtcu_tccLockSpeed[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccLockSpeed, hardCodedtcu_tccLockSpeed);
}

static void cannedtcu_tccUnlockSpeed() {
	static const float hardCodedtcu_tccUnlockSpeed[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccUnlockSpeed, hardCodedtcu_tccUnlockSpeed);
}

static void cannedtcu_pcAirmassBins() {
	static const float hardCodedtcu_pcAirmassBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcAirmassBins, hardCodedtcu_pcAirmassBins);
}

static void cannedtcu_pcValsR() {
	static const float hardCodedtcu_pcValsR[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcValsR, hardCodedtcu_pcValsR);
}

static void cannedtcu_pcValsN() {
	static const float hardCodedtcu_pcValsN[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcValsN, hardCodedtcu_pcValsN);
}

static void cannedtcu_pcVals1() {
	static const float hardCodedtcu_pcVals1[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals1, hardCodedtcu_pcVals1);
}

static void cannedtcu_pcVals2() {
	static const float hardCodedtcu_pcVals2[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals2, hardCodedtcu_pcVals2);
}

static void cannedtcu_pcVals3() {
	static const float hardCodedtcu_pcVals3[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals3, hardCodedtcu_pcVals3);
}

static void cannedtcu_pcVals4() {
	static const float hardCodedtcu_pcVals4[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals4, hardCodedtcu_pcVals4);
}

static void cannedtcu_pcVals12() {
	static const float hardCodedtcu_pcVals12[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals12, hardCodedtcu_pcVals12);
}

static void cannedtcu_pcVals23() {
	static const float hardCodedtcu_pcVals23[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals23, hardCodedtcu_pcVals23);
}

static void cannedtcu_pcVals34() {
	static const float hardCodedtcu_pcVals34[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals34, hardCodedtcu_pcVals34);
}

static void cannedtcu_pcVals21() {
	static const float hardCodedtcu_pcVals21[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals21, hardCodedtcu_pcVals21);
}

static void cannedtcu_pcVals32() {
	static const float hardCodedtcu_pcVals32[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals32, hardCodedtcu_pcVals32);
}

static void cannedtcu_pcVals43() {
	static const float hardCodedtcu_pcVals43[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals43, hardCodedtcu_pcVals43);
}

static void cannedtcu_32SpeedBins() {
	static const float hardCodedtcu_32SpeedBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_32SpeedBins, hardCodedtcu_32SpeedBins);
}

static void cannedtcu_32Vals() {
	static const float hardCodedtcu_32Vals[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_32Vals, hardCodedtcu_32Vals);
}

static void cannedtcu_rangeM() {
	static const float hardCodedtcu_rangeM[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM, hardCodedtcu_rangeM);
}

static void cannedtcu_rangeM3() {
	static const float hardCodedtcu_rangeM3[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM3, hardCodedtcu_rangeM3);
}

static void cannedtcu_rangeM2() {
	static const float hardCodedtcu_rangeM2[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM2, hardCodedtcu_rangeM2);
}

static void cannedtcu_rangeM1() {
	static const float hardCodedtcu_rangeM1[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM1, hardCodedtcu_rangeM1);
}

static void cannedignBlends1_blendBins() {
	static const float hardCodedignBlends1_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_blendBins, hardCodedignBlends1_blendBins);
}

static void cannedignBlends1_blendValues() {
	static const float hardCodedignBlends1_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_blendValues, hardCodedignBlends1_blendValues);
}

static void cannedignBlends2_blendBins() {
	static const float hardCodedignBlends2_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendBins, hardCodedignBlends2_blendBins);
}

static void cannedignBlends2_blendValues() {
	static const float hardCodedignBlends2_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendValues, hardCodedignBlends2_blendValues);
}

static void cannedignBlends3_blendBins() {
	static const float hardCodedignBlends3_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_blendBins, hardCodedignBlends3_blendBins);
}

static void cannedignBlends3_blendValues() {
	static const float hardCodedignBlends3_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_blendValues, hardCodedignBlends3_blendValues);
}

static void cannedignBlends4_blendBins() {
	static const float hardCodedignBlends4_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_blendBins, hardCodedignBlends4_blendBins);
}

static void cannedignBlends4_blendValues() {
	static const float hardCodedignBlends4_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_blendValues, hardCodedignBlends4_blendValues);
}

static void cannedveBlends1_blendBins() {
	static const float hardCodedveBlends1_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_blendBins, hardCodedveBlends1_blendBins);
}

static void cannedveBlends1_blendValues() {
	static const float hardCodedveBlends1_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_blendValues, hardCodedveBlends1_blendValues);
}

static void cannedveBlends2_blendBins() {
	static const float hardCodedveBlends2_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_blendBins, hardCodedveBlends2_blendBins);
}

static void cannedveBlends2_blendValues() {
	static const float hardCodedveBlends2_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_blendValues, hardCodedveBlends2_blendValues);
}

static void cannedveBlends3_blendBins() {
	static const float hardCodedveBlends3_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_blendBins, hardCodedveBlends3_blendBins);
}

static void cannedveBlends3_blendValues() {
	static const float hardCodedveBlends3_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_blendValues, hardCodedveBlends3_blendValues);
}

static void cannedveBlends4_blendBins() {
	static const float hardCodedveBlends4_blendBins[8] = {0.0, 14.3, 28.6, 42.9, 57.1, 71.4, 85.7, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendBins, hardCodedveBlends4_blendBins);
}

static void cannedveBlends4_blendValues() {
	static const float hardCodedveBlends4_blendValues[8] = {0.0, 14.5, 28.5, 43.0, 57.0, 71.5, 85.5, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendValues, hardCodedveBlends4_blendValues);
}

static void cannedboostOpenLoopBlends1_blendBins() {
	static const float hardCodedboostOpenLoopBlends1_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostOpenLoopBlends1_blendBins, hardCodedboostOpenLoopBlends1_blendBins);
}

static void cannedboostClosedLoopBlends2_blendBins() {
	static const float hardCodedboostClosedLoopBlends2_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_blendBins, hardCodedboostClosedLoopBlends2_blendBins);
}

static void cannedthrottleEstimateEffectiveAreaBins() {
	static const float hardCodedthrottleEstimateEffectiveAreaBins[12] = {0.0, 9.1, 18.2, 27.3, 36.4, 45.5, 54.6, 63.6, 72.7, 81.8, 90.9, 100.0};
	copyArray(config->throttleEstimateEffectiveAreaBins, hardCodedthrottleEstimateEffectiveAreaBins);
}

static void cannedtpsTpsAccelFromRpmBins() {
	static const float hardCodedtpsTpsAccelFromRpmBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelFromRpmBins, hardCodedtpsTpsAccelFromRpmBins);
}

static void cannedtpsTpsAccelToRpmBins() {
	static const float hardCodedtpsTpsAccelToRpmBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelToRpmBins, hardCodedtpsTpsAccelToRpmBins);
}

static void cannedtpsTpsAccelTable() {
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

static void cannedboostTableOpenLoop() {
	static const float hardCodedboostTableOpenLoop[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	},
{29.000,	29.000,	29.000,	29.000,	29.000,	29.000,	29.000,	29.000,	},
{43.000,	43.000,	43.000,	43.000,	43.000,	43.000,	43.000,	43.000,	},
{57.000,	57.000,	57.000,	57.000,	57.000,	57.000,	57.000,	57.000,	},
{71.000,	71.000,	71.000,	71.000,	71.000,	71.000,	71.000,	71.000,	},
{86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	},
{100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	},
};
	copyTable(config->boostTableOpenLoop, hardCodedboostTableOpenLoop);
}

static void cannedvvtTable1RpmBins() {
	static const float hardCodedvvtTable1RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->vvtTable1RpmBins, hardCodedvvtTable1RpmBins);
}

static void cannedvvtTable1LoadBins() {
	static const float hardCodedvvtTable1LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->vvtTable1LoadBins, hardCodedvvtTable1LoadBins);
}

static void cannedvvtTable1() {
	static const float hardCodedvvtTable1[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->vvtTable1, hardCodedvvtTable1);
}

static void cannedvvtTable2RpmBins() {
	static const float hardCodedvvtTable2RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->vvtTable2RpmBins, hardCodedvvtTable2RpmBins);
}

static void cannedvvtTable2LoadBins() {
	static const float hardCodedvvtTable2LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->vvtTable2LoadBins, hardCodedvvtTable2LoadBins);
}

static void cannedvvtTable2() {
	static const float hardCodedvvtTable2[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->vvtTable2, hardCodedvvtTable2);
}

static void cannedscriptTable1RpmBins() {
	static const float hardCodedscriptTable1RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable1RpmBins, hardCodedscriptTable1RpmBins);
}

static void cannedscriptTable1LoadBins() {
	static const float hardCodedscriptTable1LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable1LoadBins, hardCodedscriptTable1LoadBins);
}

static void cannedscriptTable2RpmBins() {
	static const float hardCodedscriptTable2RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable2RpmBins, hardCodedscriptTable2RpmBins);
}

static void cannedscriptTable2LoadBins() {
	static const float hardCodedscriptTable2LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable2LoadBins, hardCodedscriptTable2LoadBins);
}

static void cannedscriptTable3RpmBins() {
	static const float hardCodedscriptTable3RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable3RpmBins, hardCodedscriptTable3RpmBins);
}

static void cannedscriptTable3LoadBins() {
	static const float hardCodedscriptTable3LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable3LoadBins, hardCodedscriptTable3LoadBins);
}

static void cannedscriptTable3() {
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

static void cannedscriptTable4RpmBins() {
	static const float hardCodedscriptTable4RpmBins[10] = {650.0, 800.0, 1450.0, 2100.0, 2750.0, 3400.0, 4050.0, 4700.0, 5350.0, 7000.0};
	copyArray(config->scriptTable4RpmBins, hardCodedscriptTable4RpmBins);
}

static void cannedscriptTable4LoadBins() {
	static const float hardCodedscriptTable4LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable4LoadBins, hardCodedscriptTable4LoadBins);
}

static void cannedscriptTable4() {
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

static void cannedalsIgnRetardrpmBins() {
	static const float hardCodedalsIgnRetardrpmBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->alsIgnRetardrpmBins, hardCodedalsIgnRetardrpmBins);
}

static void cannedalsIgnRetardLoadBins() {
	static const float hardCodedalsIgnRetardLoadBins[4] = {2.0, 5.0, 7.0, 10.0};
	copyArray(config->alsIgnRetardLoadBins, hardCodedalsIgnRetardLoadBins);
}

static void cannedALSTimingRetardTable() {
	static const float hardCodedALSTimingRetardTable[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSTimingRetardTable, hardCodedALSTimingRetardTable);
}

static void cannedalsFuelAdjustmentrpmBins() {
	static const float hardCodedalsFuelAdjustmentrpmBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->alsFuelAdjustmentrpmBins, hardCodedalsFuelAdjustmentrpmBins);
}

static void cannedalsFuelAdjustmentLoadBins() {
	static const float hardCodedalsFuelAdjustmentLoadBins[4] = {2.0, 5.0, 7.0, 10.0};
	copyArray(config->alsFuelAdjustmentLoadBins, hardCodedalsFuelAdjustmentLoadBins);
}

static void cannedALSFuelAdjustment() {
	static const float hardCodedALSFuelAdjustment[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSFuelAdjustment, hardCodedALSFuelAdjustment);
}

static void cannedalsIgnSkiprpmBins() {
	static const float hardCodedalsIgnSkiprpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->alsIgnSkiprpmBins, hardCodedalsIgnSkiprpmBins);
}

static void cannedalsIgnSkipLoadBins() {
	static const float hardCodedalsIgnSkipLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->alsIgnSkipLoadBins, hardCodedalsIgnSkipLoadBins);
}

static void cannedALSIgnSkipTable() {
	static const float hardCodedALSIgnSkipTable[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSIgnSkipTable, hardCodedALSIgnSkipTable);
}

static void cannedignitionRpmBins() {
	static const float hardCodedignitionRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->ignitionRpmBins, hardCodedignitionRpmBins);
}

static void cannedignitionLoadBins() {
	static const float hardCodedignitionLoadBins[16] = {21.0, 27.0, 33.0, 39.0, 48.0, 54.0, 60.0, 66.0, 72.0, 81.0, 87.0, 93.0, 99.0, 108.0, 114.0, 120.0};
	copyArray(config->ignitionLoadBins, hardCodedignitionLoadBins);
}

static void cannedignitionTable() {
	static const float hardCodedignitionTable[16][16] = {
{15.400,	15.800,	16.600,	17.600,	24.900,	28.900,	32.800,	36.700,	37.700,	39.000,	39.000,	39.000,	39.000,	39.000,	39.000,	39.000,	},
{15.300,	15.600,	16.400,	17.300,	24.600,	28.500,	32.300,	36.200,	37.100,	38.400,	38.400,	38.400,	38.400,	38.400,	38.400,	38.400,	},
{17.000,	18.900,	16.700,	20.500,	24.300,	28.100,	31.800,	35.600,	36.500,	37.800,	37.800,	37.800,	37.800,	37.800,	37.800,	37.800,	},
{16.800,	18.700,	16.400,	20.200,	23.900,	27.700,	31.400,	35.100,	36.000,	37.200,	37.200,	37.200,	37.200,	37.200,	37.200,	37.200,	},
{16.600,	18.500,	16.100,	19.800,	23.400,	27.100,	30.700,	34.300,	35.100,	36.300,	36.300,	36.300,	36.300,	36.300,	36.300,	36.300,	},
{16.500,	18.300,	15.900,	19.500,	23.100,	26.700,	30.200,	33.800,	34.500,	35.700,	35.700,	35.700,	35.700,	35.700,	35.700,	35.700,	},
{16.400,	18.200,	15.700,	19.200,	22.700,	26.300,	29.800,	33.300,	33.900,	35.100,	35.100,	35.100,	35.100,	35.100,	35.100,	35.100,	},
{11.100,	12.800,	10.300,	13.700,	22.400,	25.900,	29.300,	32.800,	33.300,	34.500,	34.500,	34.500,	34.500,	34.500,	34.500,	34.500,	},
{9.000,	10.700,	8.100,	11.500,	22.000,	25.500,	28.900,	32.300,	34.500,	35.600,	35.600,	35.600,	33.200,	33.200,	33.200,	33.200,	},
{8.500,	10.200,	7.500,	10.800,	21.500,	24.900,	28.200,	31.500,	33.600,	34.700,	34.700,	34.700,	32.300,	32.300,	32.300,	32.300,	},
{5.800,	7.400,	4.700,	7.900,	21.200,	24.500,	27.700,	31.000,	33.000,	34.100,	34.100,	34.100,	31.700,	31.700,	31.700,	31.700,	},
{-2.300,	-0.700,	-3.500,	-0.300,	20.900,	24.100,	27.200,	30.400,	32.400,	33.500,	33.500,	33.500,	31.100,	31.100,	31.100,	31.100,	},
{-2.500,	-0.900,	-3.800,	-0.600,	20.500,	23.700,	26.800,	29.900,	31.900,	32.900,	32.900,	32.900,	30.500,	30.500,	30.500,	30.500,	},
{-2.500,	-0.900,	-3.800,	-0.700,	20.500,	23.600,	26.700,	29.800,	31.800,	32.800,	32.800,	32.800,	30.400,	30.400,	30.400,	30.400,	},
{-2.500,	-0.900,	-3.800,	-0.700,	20.500,	23.600,	26.700,	29.800,	31.800,	32.800,	32.800,	32.800,	30.400,	30.400,	30.400,	30.400,	},
{-2.500,	-0.900,	-3.800,	-0.700,	20.500,	23.600,	26.700,	29.800,	31.800,	32.800,	32.800,	32.800,	30.400,	30.400,	30.400,	30.400,	},
};
	copyTable(config->ignitionTable, hardCodedignitionTable);
}

static void cannedignBlends1_rpmBins() {
	static const float hardCodedignBlends1_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_rpmBins, hardCodedignBlends1_rpmBins);
}

static void cannedignBlends1_loadBins() {
	static const float hardCodedignBlends1_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_loadBins, hardCodedignBlends1_loadBins);
}

static void cannedignBlends1_table() {
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

static void cannedignBlends2_rpmBins() {
	static const float hardCodedignBlends2_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_rpmBins, hardCodedignBlends2_rpmBins);
}

static void cannedignBlends2_loadBins() {
	static const float hardCodedignBlends2_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_loadBins, hardCodedignBlends2_loadBins);
}

static void cannedignBlends2_table() {
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

static void cannedignBlends3_rpmBins() {
	static const float hardCodedignBlends3_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_rpmBins, hardCodedignBlends3_rpmBins);
}

static void cannedignBlends3_loadBins() {
	static const float hardCodedignBlends3_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends3_loadBins, hardCodedignBlends3_loadBins);
}

static void cannedignBlends3_table() {
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

static void cannedignBlends4_rpmBins() {
	static const float hardCodedignBlends4_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_rpmBins, hardCodedignBlends4_rpmBins);
}

static void cannedignBlends4_loadBins() {
	static const float hardCodedignBlends4_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends4_loadBins, hardCodedignBlends4_loadBins);
}

static void cannedveBlends1_rpmBins() {
	static const float hardCodedveBlends1_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_rpmBins, hardCodedveBlends1_rpmBins);
}

static void cannedveBlends1_loadBins() {
	static const float hardCodedveBlends1_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends1_loadBins, hardCodedveBlends1_loadBins);
}

static void cannedveBlends1_table() {
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

static void cannedveBlends2_rpmBins() {
	static const float hardCodedveBlends2_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_rpmBins, hardCodedveBlends2_rpmBins);
}

static void cannedveBlends2_loadBins() {
	static const float hardCodedveBlends2_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_loadBins, hardCodedveBlends2_loadBins);
}

static void cannedveBlends2_table() {
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

static void cannedveBlends3_rpmBins() {
	static const float hardCodedveBlends3_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_rpmBins, hardCodedveBlends3_rpmBins);
}

static void cannedveBlends3_loadBins() {
	static const float hardCodedveBlends3_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_loadBins, hardCodedveBlends3_loadBins);
}

static void cannedveBlends3_table() {
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

static void cannedveBlends4_rpmBins() {
	static const float hardCodedveBlends4_rpmBins[8] = {0.0, 1000.0, 2000.0, 3000.0, 4000.0, 5000.0, 6000.0, 7000.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_rpmBins, hardCodedveBlends4_rpmBins);
}

static void cannedveBlends4_loadBins() {
	static const float hardCodedveBlends4_loadBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_loadBins, hardCodedveBlends4_loadBins);
}

static void cannedboostOpenLoopBlends1_rpmBins() {
	static const float hardCodedboostOpenLoopBlends1_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostOpenLoopBlends1_rpmBins, hardCodedboostOpenLoopBlends1_rpmBins);
}

static void cannedboostClosedLoopBlends1_table() {
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

static void cannedboostClosedLoopBlends2_rpmBins() {
	static const float hardCodedboostClosedLoopBlends2_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_rpmBins, hardCodedboostClosedLoopBlends2_rpmBins);
}

static void cannedboostClosedLoopBlends2_loadBins() {
	static const float hardCodedboostClosedLoopBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_loadBins, hardCodedboostClosedLoopBlends2_loadBins);
}

static void cannedboostClosedLoopBlends2_table() {
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

static void cannedignitionIatCorrTempBins() {
	static const float hardCodedignitionIatCorrTempBins[8] = {-40.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0};
	copyArray(config->ignitionIatCorrTempBins, hardCodedignitionIatCorrTempBins);
}

static void cannedignitionIatCorrLoadBins() {
	static const float hardCodedignitionIatCorrLoadBins[8] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0, 120.0, 140.0};
	copyArray(config->ignitionIatCorrLoadBins, hardCodedignitionIatCorrLoadBins);
}

static void cannedignitionIatCorrTable() {
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

static void cannedveRpmBins() {
	static const float hardCodedveRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->veRpmBins, hardCodedveRpmBins);
}

static void cannedveLoadBins() {
	static const float hardCodedveLoadBins[16] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 140.0, 150.0, 160.0};
	copyArray(config->veLoadBins, hardCodedveLoadBins);
}

static void cannedveTable() {
	static const float hardCodedveTable[16][16] = {
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
{80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	80.000,	},
};
	copyTable(config->veTable, hardCodedveTable);
}

static void cannedfuelTrimRpmBins() {
	static const float hardCodedfuelTrimRpmBins[4] = {1000.0, 3000.0, 5000.0, 7000.0};
	copyArray(config->fuelTrimRpmBins, hardCodedfuelTrimRpmBins);
}

static void cannedfuelTrimLoadBins() {
	static const float hardCodedfuelTrimLoadBins[4] = {20.0, 50.0, 80.0, 100.0};
	copyArray(config->fuelTrimLoadBins, hardCodedfuelTrimLoadBins);
}

static void cannedfuelTrims1_table() {
	static const float hardCodedfuelTrims1_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims1_table, hardCodedfuelTrims1_table);
}

static void cannedfuelTrims2_table() {
	static const float hardCodedfuelTrims2_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims2_table, hardCodedfuelTrims2_table);
}

static void cannedfuelTrims3_table() {
	static const float hardCodedfuelTrims3_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims3_table, hardCodedfuelTrims3_table);
}

static void cannedfuelTrims4_table() {
	static const float hardCodedfuelTrims4_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims4_table, hardCodedfuelTrims4_table);
}

static void cannedfuelTrims5_table() {
	static const float hardCodedfuelTrims5_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims5_table, hardCodedfuelTrims5_table);
}

static void cannedfuelTrims6_table() {
	static const float hardCodedfuelTrims6_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims6_table, hardCodedfuelTrims6_table);
}

static void cannedfuelTrims7_table() {
	static const float hardCodedfuelTrims7_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims7_table, hardCodedfuelTrims7_table);
}

static void cannedfuelTrims8_table() {
	static const float hardCodedfuelTrims8_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims8_table, hardCodedfuelTrims8_table);
}

static void cannedfuelTrims9_table() {
	static const float hardCodedfuelTrims9_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims9_table, hardCodedfuelTrims9_table);
}

static void cannedfuelTrims10_table() {
	static const float hardCodedfuelTrims10_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims10_table, hardCodedfuelTrims10_table);
}

static void cannedfuelTrims11_table() {
	static const float hardCodedfuelTrims11_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims11_table, hardCodedfuelTrims11_table);
}

static void cannedfuelTrims12_table() {
	static const float hardCodedfuelTrims12_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims12_table, hardCodedfuelTrims12_table);
}

static void cannedignTrimRpmBins() {
	static const float hardCodedignTrimRpmBins[4] = {1000.0, 3000.0, 5000.0, 7000.0};
	copyArray(config->ignTrimRpmBins, hardCodedignTrimRpmBins);
}

static void cannedignTrimLoadBins() {
	static const float hardCodedignTrimLoadBins[4] = {20.0, 50.0, 80.0, 100.0};
	copyArray(config->ignTrimLoadBins, hardCodedignTrimLoadBins);
}

static void cannedignTrims1_table() {
	static const float hardCodedignTrims1_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims1_table, hardCodedignTrims1_table);
}

static void cannedignTrims2_table() {
	static const float hardCodedignTrims2_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims2_table, hardCodedignTrims2_table);
}

static void cannedignTrims3_table() {
	static const float hardCodedignTrims3_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims3_table, hardCodedignTrims3_table);
}

static void cannedignTrims4_table() {
	static const float hardCodedignTrims4_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims4_table, hardCodedignTrims4_table);
}

static void cannedignTrims5_table() {
	static const float hardCodedignTrims5_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims5_table, hardCodedignTrims5_table);
}

static void cannedignTrims6_table() {
	static const float hardCodedignTrims6_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims6_table, hardCodedignTrims6_table);
}

static void cannedignTrims7_table() {
	static const float hardCodedignTrims7_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims7_table, hardCodedignTrims7_table);
}

static void cannedignTrims8_table() {
	static const float hardCodedignTrims8_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims8_table, hardCodedignTrims8_table);
}

static void cannedignTrims9_table() {
	static const float hardCodedignTrims9_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims9_table, hardCodedignTrims9_table);
}

static void cannedignTrims10_table() {
	static const float hardCodedignTrims10_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims10_table, hardCodedignTrims10_table);
}

static void cannedignTrims11_table() {
	static const float hardCodedignTrims11_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims11_table, hardCodedignTrims11_table);
}

static void cannedignTrims12_table() {
	static const float hardCodedignTrims12_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims12_table, hardCodedignTrims12_table);
}

static void cannedmapEstimateRpmBins() {
	static const float hardCodedmapEstimateRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->mapEstimateRpmBins, hardCodedmapEstimateRpmBins);
}

static void cannedmapEstimateTpsBins() {
	static const float hardCodedmapEstimateTpsBins[16] = {0.0, 6.67, 13.33, 20.0, 26.67, 33.33, 40.0, 46.67, 53.33, 60.0, 66.67, 73.33, 80.0, 86.67, 93.33, 100.0};
	copyArray(config->mapEstimateTpsBins, hardCodedmapEstimateTpsBins);
}

static void cannedmapEstimateTable() {
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

static void cannedinjPhaseRpmBins() {
	static const float hardCodedinjPhaseRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->injPhaseRpmBins, hardCodedinjPhaseRpmBins);
}

static void cannedinjPhaseLoadBins() {
	static const float hardCodedinjPhaseLoadBins[16] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 140.0, 150.0, 160.0};
	copyArray(config->injPhaseLoadBins, hardCodedinjPhaseLoadBins);
}

static void cannedinjectionPhase() {
	static const float hardCodedinjectionPhase[16][16] = {
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
{-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	-400.000,	},
};
	copyTable(config->injectionPhase, hardCodedinjectionPhase);
}

static void cannedthrottle2TrimRpmBins() {
	static const float hardCodedthrottle2TrimRpmBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->throttle2TrimRpmBins, hardCodedthrottle2TrimRpmBins);
}

static void cannedthrottle2TrimTpsBins() {
	static const float hardCodedthrottle2TrimTpsBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->throttle2TrimTpsBins, hardCodedthrottle2TrimTpsBins);
}

static void cannedthrottle2TrimTable() {
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

static void cannedmaxKnockRetardRpmBins() {
	static const float hardCodedmaxKnockRetardRpmBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->maxKnockRetardRpmBins, hardCodedmaxKnockRetardRpmBins);
}

static void cannedmaxKnockRetardLoadBins() {
	static const float hardCodedmaxKnockRetardLoadBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->maxKnockRetardLoadBins, hardCodedmaxKnockRetardLoadBins);
}

static void cannedmaxKnockRetardTable() {
	static const float hardCodedmaxKnockRetardTable[6][6] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->maxKnockRetardTable, hardCodedmaxKnockRetardTable);
}

static void cannedlambdaRpmBins() {
	static const float hardCodedlambdaRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->lambdaRpmBins, hardCodedlambdaRpmBins);
}

static void cannedlambdaLoadBins() {
	static const float hardCodedlambdaLoadBins[16] = {30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 150.0, 175.0, 200.0, 225.0, 250.0};
	copyArray(config->lambdaLoadBins, hardCodedlambdaLoadBins);
}

static void cannedlambdaTable() {
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

static void cannedgppwm1_rpmBins() {
	static const float hardCodedgppwm1_rpmBins[8] = {0.0, 2000.0, 3000.0, 4000.0, 4500.0, 5000.0, 5500.0, 7000.0};
	copyArray(engineConfiguration->gppwm4.gppwm1_rpmBins, hardCodedgppwm1_rpmBins);
}

static void cannedgppwm1_table() {
	static const float hardCodedgppwm1_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	},
{0.000,	0.000,	0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	},
{0.000,	0.000,	0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	},
{0.000,	0.000,	0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	},
};
	copyTable(engineConfiguration->gppwm4.gppwm1_table, hardCodedgppwm1_table);
}

static void cannedinjectorStagingRpmBins() {
	static const float hardCodedinjectorStagingRpmBins[6] = {650.0, 800.0, 2200.0, 3600.0, 5000.0, 7000.0};
	copyArray(config->injectorStagingRpmBins, hardCodedinjectorStagingRpmBins);
}

static void cannedinjectorStagingLoadBins() {
	static const float hardCodedinjectorStagingLoadBins[6] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->injectorStagingLoadBins, hardCodedinjectorStagingLoadBins);
}

static void cannedinjectorStagingTable() {
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

static void cannedhpfpTargetRpmBins() {
	static const float hardCodedhpfpTargetRpmBins[10] = {650.0, 800.0, 1450.0, 2100.0, 2750.0, 3400.0, 4050.0, 4700.0, 5350.0, 7000.0};
	copyArray(config->hpfpTargetRpmBins, hardCodedhpfpTargetRpmBins);
}

static void cannedhpfpTargetLoadBins() {
	static const float hardCodedhpfpTargetLoadBins[10] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0, 120.0, 140.0, 160.0, 180.0};
	copyArray(config->hpfpTargetLoadBins, hardCodedhpfpTargetLoadBins);
}

static void cannedhpfpCompensationRpmBins() {
	static const float hardCodedhpfpCompensationRpmBins[10] = {650.0, 800.0, 1450.0, 2100.0, 2750.0, 3400.0, 4050.0, 4700.0, 5350.0, 7000.0};
	copyArray(config->hpfpCompensationRpmBins, hardCodedhpfpCompensationRpmBins);
}

static void cannedhpfpCompensationLoadBins() {
	static const float hardCodedhpfpCompensationLoadBins[10] = {0.005, 0.018, 0.031, 0.043, 0.056, 0.069, 0.082, 0.094, 0.107, 0.12};
	copyArray(config->hpfpCompensationLoadBins, hardCodedhpfpCompensationLoadBins);
}

static void cannedhpfpCompensation() {
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

```
