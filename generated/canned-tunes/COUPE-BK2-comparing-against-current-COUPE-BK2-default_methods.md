```
static void coupleBK2cannedknockNoiseRpmBins() {
	static const float hardCodedknockNoiseRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->knockNoiseRpmBins, hardCodedknockNoiseRpmBins);
}

static void coupleBK2cannedknockBaseNoise() {
	static const float hardCodedknockBaseNoise[16] = {-20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0, -20.0};
	copyArray(config->knockBaseNoise, hardCodedknockBaseNoise);
}

static void coupleBK2canneddwellVoltageCorrVoltBins() {
	static const float hardCodeddwellVoltageCorrVoltBins[8] = {8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 14.0, 15.0};
	copyArray(config->dwellVoltageCorrVoltBins, hardCodeddwellVoltageCorrVoltBins);
}

static void coupleBK2canneddwellVoltageCorrValues() {
	static const float hardCodeddwellVoltageCorrValues[8] = {1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->dwellVoltageCorrValues, hardCodeddwellVoltageCorrValues);
}

static void coupleBK2cannedtpsTspCorrValuesBins() {
	static const float hardCodedtpsTspCorrValuesBins[4] = {1000.0, 3000.0, 5000.0, 7000.0};
	copyArray(config->tpsTspCorrValuesBins, hardCodedtpsTspCorrValuesBins);
}

static void coupleBK2cannedtpsTspCorrValues() {
	static const float hardCodedtpsTspCorrValues[4] = {1.0, 0.7, 0.3, 0.1};
	copyArray(config->tpsTspCorrValues, hardCodedtpsTspCorrValues);
}

static void coupleBK2cannedprimeBins() {
	static const float hardCodedprimeBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->primeBins, hardCodedprimeBins);
}

static void coupleBK2cannedprimeValues() {
	static const float hardCodedprimeValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->primeValues, hardCodedprimeValues);
}

static void coupleBK2cannedmap_samplingAngleBins() {
	static const float hardCodedmap_samplingAngleBins[8] = {800.0, 1686.0, 2571.0, 3457.0, 4343.0, 5229.0, 6114.0, 7000.0};
	copyArray(engineConfiguration->map.map_samplingAngleBins, hardCodedmap_samplingAngleBins);
}

static void coupleBK2cannedmap_samplingWindowBins() {
	static const float hardCodedmap_samplingWindowBins[8] = {800.0, 1686.0, 2571.0, 3457.0, 4343.0, 5229.0, 6114.0, 7000.0};
	copyArray(engineConfiguration->map.map_samplingWindowBins, hardCodedmap_samplingWindowBins);
}

static void coupleBK2cannedvrThreshold1_rpmBins() {
	static const float hardCodedvrThreshold1_rpmBins[6] = {600.0, 1900.0, 3200.0, 4400.0, 5700.0, 7000.0};
	copyArray(engineConfiguration->vrThreshold2.vrThreshold1_rpmBins, hardCodedvrThreshold1_rpmBins);
}

static void coupleBK2cannedvrThreshold2_rpmBins() {
	static const float hardCodedvrThreshold2_rpmBins[6] = {600.0, 1900.0, 3200.0, 4400.0, 5700.0, 7000.0};
	copyArray(engineConfiguration->vrThreshold2.vrThreshold2_rpmBins, hardCodedvrThreshold2_rpmBins);
}

static void coupleBK2cannedmafDecodingBins() {
	static const float hardCodedmafDecodingBins[32] = {0.0, 0.78125, 1.3867188, 2.9101562, 4.2578125, 4.9804688, 2016.0, 2017.0, 2018.0, 2019.0, 2020.0, 2021.0, 2022.0, 2023.0, 2024.0, 2025.0, 2026.0, 2027.0, 2028.0, 2029.0, 2030.0, 2031.0, 2032.0, 2033.0, 2034.0, 2035.0, 2036.0, 2037.0, 2038.0, 2039.0, 2040.0, 2041.0};
	copyArray(config->mafDecodingBins, hardCodedmafDecodingBins);
}

static void coupleBK2cannedmafDecoding() {
	static const float hardCodedmafDecoding[32] = {-34.5, -6.0, 10.5, 105.3, 387.5, 738.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0, 3000.0};
	copyArray(config->mafDecoding, hardCodedmafDecoding);
}

static void coupleBK2cannediatFuelCorrBins() {
	static const float hardCodediatFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->iatFuelCorrBins, hardCodediatFuelCorrBins);
}

static void coupleBK2cannediatFuelCorr() {
	static const float hardCodediatFuelCorr[16] = {1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->iatFuelCorr, hardCodediatFuelCorr);
}

static void coupleBK2cannedcltFuelCorrBins() {
	static const float hardCodedcltFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->cltFuelCorrBins, hardCodedcltFuelCorrBins);
}

static void coupleBK2cannedcltFuelCorr() {
	static const float hardCodedcltFuelCorr[16] = {1.5, 1.5, 1.42, 1.36, 1.28, 1.19, 1.12, 1.1, 1.06, 1.06, 1.03, 1.01, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->cltFuelCorr, hardCodedcltFuelCorr);
}

static void coupleBK2cannedcrankingFuelBins() {
	static const float hardCodedcrankingFuelBins[8] = {-20.0, -10.0, 5.0, 20.0, 35.0, 50.0, 65.0, 90.0};
	copyArray(config->crankingFuelBins, hardCodedcrankingFuelBins);
}

static void coupleBK2cannedcrankingFuelCoef() {
	static const float hardCodedcrankingFuelCoef[8] = {2.8, 2.2, 1.8, 1.55, 1.3, 1.1, 1.0, 1.0};
	copyArray(config->crankingFuelCoef, hardCodedcrankingFuelCoef);
}

static void coupleBK2cannedcrankingFuelCoefE100() {
	static const float hardCodedcrankingFuelCoefE100[8] = {2.8, 2.2, 1.8, 1.55, 1.3, 1.1, 1.0, 1.0};
	copyArray(config->crankingFuelCoefE100, hardCodedcrankingFuelCoefE100);
}

static void coupleBK2cannedcltRevLimitRpmBins() {
	static const float hardCodedcltRevLimitRpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->cltRevLimitRpmBins, hardCodedcltRevLimitRpmBins);
}

static void coupleBK2cannedcltRevLimitRpm() {
	static const float hardCodedcltRevLimitRpm[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->cltRevLimitRpm, hardCodedcltRevLimitRpm);
}

static void coupleBK2cannedcltIdleCorrBins() {
	static const float hardCodedcltIdleCorrBins[16] = {-40.13, -30.13, -20.13, -10.13, -0.13, 9.87, 19.87, 29.87, 39.87, 49.87, 59.87, 69.87, 79.87, 89.87, 99.87, 109.87};
	copyArray(config->cltIdleCorrBins, hardCodedcltIdleCorrBins);
}

static void coupleBK2cannedcltIdleCorr() {
	static const float hardCodedcltIdleCorr[16] = {0.87, 0.87, 0.7033, 0.7033, 0.7033, 0.7033, 0.7033, 0.7033, 0.7033, 0.6033, 0.5367, 0.5, 0.5, 0.5, 0.5, 0.6};
	copyArray(config->cltIdleCorr, hardCodedcltIdleCorr);
}

static void coupleBK2cannedcltCrankingCorr() {
	static const float hardCodedcltCrankingCorr[8] = {0.8, 0.8, 0.8, 0.8, 0.7, 0.64, 0.6, 0.6};
	copyArray(config->cltCrankingCorr, hardCodedcltCrankingCorr);
}

static void coupleBK2cannedcltIdleRpm() {
	static const float hardCodedcltIdleRpm[16] = {1360.0, 1360.0, 1300.0, 1200.0, 1160.0, 1100.0, 1060.0, 1000.0, 1000.0, 960.0, 960.0, 940.0, 900.0, 800.0, 860.0, 1100.0};
	copyArray(config->cltIdleRpm, hardCodedcltIdleRpm);
}

static void coupleBK2cannedidleAdvanceBins() {
	static const float hardCodedidleAdvanceBins[8] = {500.0, 650.0, 800.0, 950.0, 1050.0, 1200.0, 1350.0, 1500.0};
	copyArray(config->idleAdvanceBins, hardCodedidleAdvanceBins);
}

static void coupleBK2cannedidleAdvance() {
	static const float hardCodedidleAdvance[8] = {10.0, 10.285714, 10.571428, 10.857142, 11.142858, 11.428572, 11.714286, 12.0};
	copyArray(config->idleAdvance, hardCodedidleAdvance);
}

static void coupleBK2cannedfuelLevelBins() {
	static const float hardCodedfuelLevelBins[8] = {0.0, 0.71, 1.43, 2.14, 2.86, 3.57, 4.29, 5.0};
	copyArray(config->fuelLevelBins, hardCodedfuelLevelBins);
}

static void coupleBK2cannedfuelLevelValues() {
	static const float hardCodedfuelLevelValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelLevelValues, hardCodedfuelLevelValues);
}

static void coupleBK2cannedhpfpLobeProfileQuantityBins() {
	static const float hardCodedhpfpLobeProfileQuantityBins[16] = {0.0, 1.0, 4.5, 9.5, 16.5, 25.0, 34.5, 45.0, 55.0, 65.5, 75.0, 83.5, 90.5, 95.5, 99.0, 100.0};
	copyArray(config->hpfpLobeProfileQuantityBins, hardCodedhpfpLobeProfileQuantityBins);
}

static void coupleBK2cannedhpfpLobeProfileAngle() {
	static const float hardCodedhpfpLobeProfileAngle[16] = {0.0, 7.5, 16.5, 24.0, 32.0, 40.0, 48.0, 56.0, 64.0, 72.0, 80.0, 88.0, 96.0, 103.5, 112.5, 120.0};
	copyArray(config->hpfpLobeProfileAngle, hardCodedhpfpLobeProfileAngle);
}

static void coupleBK2cannedhpfpDeadtimeVoltsBins() {
	static const float hardCodedhpfpDeadtimeVoltsBins[8] = {8.0, 9.0, 10.0, 11.0, 12.0, 13.0, 15.0, 16.0};
	copyArray(config->hpfpDeadtimeVoltsBins, hardCodedhpfpDeadtimeVoltsBins);
}

static void coupleBK2cannedwwCltBins() {
	static const float hardCodedwwCltBins[8] = {-40.0, -20.0, 0.0, 20.0, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->wwCltBins, hardCodedwwCltBins);
}

static void coupleBK2cannedwwTauCltValues() {
	static const float hardCodedwwTauCltValues[8] = {1.45, 1.3, 1.17, 1.05, 0.9, 0.82, 0.75, 0.7};
	copyArray(config->wwTauCltValues, hardCodedwwTauCltValues);
}

static void coupleBK2cannedwwMapBins() {
	static const float hardCodedwwMapBins[8] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0};
	copyArray(config->wwMapBins, hardCodedwwMapBins);
}

static void coupleBK2cannedwwTauMapValues() {
	static const float hardCodedwwTauMapValues[8] = {0.38, 0.55, 0.69, 0.86, 0.9, 0.95, 0.97, 1.0};
	copyArray(config->wwTauMapValues, hardCodedwwTauMapValues);
}

static void coupleBK2cannedwwBetaCltValues() {
	static const float hardCodedwwBetaCltValues[8] = {0.73, 0.66, 0.57, 0.46, 0.38, 0.31, 0.24, 0.19};
	copyArray(config->wwBetaCltValues, hardCodedwwBetaCltValues);
}

static void coupleBK2cannedwwBetaMapValues() {
	static const float hardCodedwwBetaMapValues[8] = {0.21, 0.4, 0.6, 0.79, 0.85, 0.9, 0.95, 1.0};
	copyArray(config->wwBetaMapValues, hardCodedwwBetaMapValues);
}

static void coupleBK2cannedtcu_tccTpsBins() {
	static const float hardCodedtcu_tccTpsBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccTpsBins, hardCodedtcu_tccTpsBins);
}

static void coupleBK2cannedtcu_tccLockSpeed() {
	static const float hardCodedtcu_tccLockSpeed[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccLockSpeed, hardCodedtcu_tccLockSpeed);
}

static void coupleBK2cannedtcu_tccUnlockSpeed() {
	static const float hardCodedtcu_tccUnlockSpeed[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_tccUnlockSpeed, hardCodedtcu_tccUnlockSpeed);
}

static void coupleBK2cannedtcu_pcAirmassBins() {
	static const float hardCodedtcu_pcAirmassBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcAirmassBins, hardCodedtcu_pcAirmassBins);
}

static void coupleBK2cannedtcu_pcValsR() {
	static const float hardCodedtcu_pcValsR[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcValsR, hardCodedtcu_pcValsR);
}

static void coupleBK2cannedtcu_pcValsN() {
	static const float hardCodedtcu_pcValsN[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcValsN, hardCodedtcu_pcValsN);
}

static void coupleBK2cannedtcu_pcVals1() {
	static const float hardCodedtcu_pcVals1[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals1, hardCodedtcu_pcVals1);
}

static void coupleBK2cannedtcu_pcVals2() {
	static const float hardCodedtcu_pcVals2[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals2, hardCodedtcu_pcVals2);
}

static void coupleBK2cannedtcu_pcVals3() {
	static const float hardCodedtcu_pcVals3[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals3, hardCodedtcu_pcVals3);
}

static void coupleBK2cannedtcu_pcVals4() {
	static const float hardCodedtcu_pcVals4[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals4, hardCodedtcu_pcVals4);
}

static void coupleBK2cannedtcu_pcVals12() {
	static const float hardCodedtcu_pcVals12[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals12, hardCodedtcu_pcVals12);
}

static void coupleBK2cannedtcu_pcVals23() {
	static const float hardCodedtcu_pcVals23[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals23, hardCodedtcu_pcVals23);
}

static void coupleBK2cannedtcu_pcVals34() {
	static const float hardCodedtcu_pcVals34[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals34, hardCodedtcu_pcVals34);
}

static void coupleBK2cannedtcu_pcVals21() {
	static const float hardCodedtcu_pcVals21[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals21, hardCodedtcu_pcVals21);
}

static void coupleBK2cannedtcu_pcVals32() {
	static const float hardCodedtcu_pcVals32[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals32, hardCodedtcu_pcVals32);
}

static void coupleBK2cannedtcu_pcVals43() {
	static const float hardCodedtcu_pcVals43[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_pcVals43, hardCodedtcu_pcVals43);
}

static void coupleBK2cannedtcu_32SpeedBins() {
	static const float hardCodedtcu_32SpeedBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_32SpeedBins, hardCodedtcu_32SpeedBins);
}

static void coupleBK2cannedtcu_32Vals() {
	static const float hardCodedtcu_32Vals[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_32Vals, hardCodedtcu_32Vals);
}

static void coupleBK2cannedtcu_rangeM() {
	static const float hardCodedtcu_rangeM[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM, hardCodedtcu_rangeM);
}

static void coupleBK2cannedtcu_rangeM3() {
	static const float hardCodedtcu_rangeM3[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM3, hardCodedtcu_rangeM3);
}

static void coupleBK2cannedtcu_rangeM2() {
	static const float hardCodedtcu_rangeM2[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM2, hardCodedtcu_rangeM2);
}

static void coupleBK2cannedtcu_rangeM1() {
	static const float hardCodedtcu_rangeM1[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->tcu_rangeM1, hardCodedtcu_rangeM1);
}

static void coupleBK2cannedignBlends1_blendBins() {
	static const float hardCodedignBlends1_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_blendBins, hardCodedignBlends1_blendBins);
}

static void coupleBK2cannedignBlends2_blendBins() {
	static const float hardCodedignBlends2_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendBins, hardCodedignBlends2_blendBins);
}

static void coupleBK2cannedignBlends2_blendValues() {
	static const float hardCodedignBlends2_blendValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendValues, hardCodedignBlends2_blendValues);
}

static void coupleBK2cannedveBlends3_blendBins() {
	static const float hardCodedveBlends3_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_blendBins, hardCodedveBlends3_blendBins);
}

static void coupleBK2cannedveBlends4_blendBins() {
	static const float hardCodedveBlends4_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendBins, hardCodedveBlends4_blendBins);
}

static void coupleBK2cannedveBlends4_blendValues() {
	static const float hardCodedveBlends4_blendValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendValues, hardCodedveBlends4_blendValues);
}

static void coupleBK2cannedboostOpenLoopBlends1_blendBins() {
	static const float hardCodedboostOpenLoopBlends1_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostOpenLoopBlends1_blendBins, hardCodedboostOpenLoopBlends1_blendBins);
}

static void coupleBK2cannedboostClosedLoopBlends2_blendBins() {
	static const float hardCodedboostClosedLoopBlends2_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_blendBins, hardCodedboostClosedLoopBlends2_blendBins);
}

static void coupleBK2cannedthrottleEstimateEffectiveAreaBins() {
	static const float hardCodedthrottleEstimateEffectiveAreaBins[12] = {0.0, 9.1, 18.2, 27.3, 36.4, 45.5, 54.6, 63.6, 72.7, 81.8, 90.9, 100.0};
	copyArray(config->throttleEstimateEffectiveAreaBins, hardCodedthrottleEstimateEffectiveAreaBins);
}

static void coupleBK2cannedtpsTpsAccelFromRpmBins() {
	static const float hardCodedtpsTpsAccelFromRpmBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelFromRpmBins, hardCodedtpsTpsAccelFromRpmBins);
}

static void coupleBK2cannedtpsTpsAccelToRpmBins() {
	static const float hardCodedtpsTpsAccelToRpmBins[8] = {0.0, 10.0, 30.0, 40.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelToRpmBins, hardCodedtpsTpsAccelToRpmBins);
}

static void coupleBK2cannedtpsTpsAccelTable() {
	static const float hardCodedtpsTpsAccelTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{5.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{8.500,	5.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{11.500,	8.500,	5.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{14.000,	11.500,	8.500,	5.000,	0.000,	0.000,	0.000,	0.000,	},
{16.000,	14.000,	11.500,	8.500,	5.000,	0.000,	0.000,	0.000,	},
{17.500,	16.000,	14.000,	11.500,	8.500,	5.000,	0.000,	0.000,	},
{18.500,	17.500,	16.000,	14.000,	11.500,	8.500,	5.000,	0.000,	},
};
	copyTable(config->tpsTpsAccelTable, hardCodedtpsTpsAccelTable);
}

static void coupleBK2cannedboostRpmBins() {
	static const float hardCodedboostRpmBins[8] = {0.0, 1100.0, 2300.0, 3400.0, 4600.0, 5700.0, 6900.0, 8000.0};
	copyArray(config->boostRpmBins, hardCodedboostRpmBins);
}

static void coupleBK2cannedboostTableOpenLoop() {
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

static void coupleBK2cannedvvtTable1RpmBins() {
	static const float hardCodedvvtTable1RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->vvtTable1RpmBins, hardCodedvvtTable1RpmBins);
}

static void coupleBK2cannedvvtTable1LoadBins() {
	static const float hardCodedvvtTable1LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->vvtTable1LoadBins, hardCodedvvtTable1LoadBins);
}

static void coupleBK2cannedvvtTable1() {
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

static void coupleBK2cannedvvtTable2RpmBins() {
	static const float hardCodedvvtTable2RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->vvtTable2RpmBins, hardCodedvvtTable2RpmBins);
}

static void coupleBK2cannedvvtTable2LoadBins() {
	static const float hardCodedvvtTable2LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->vvtTable2LoadBins, hardCodedvvtTable2LoadBins);
}

static void coupleBK2cannedvvtTable2() {
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

static void coupleBK2cannedscriptTable1RpmBins() {
	static const float hardCodedscriptTable1RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable1RpmBins, hardCodedscriptTable1RpmBins);
}

static void coupleBK2cannedscriptTable1LoadBins() {
	static const float hardCodedscriptTable1LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable1LoadBins, hardCodedscriptTable1LoadBins);
}

static void coupleBK2cannedscriptTable2RpmBins() {
	static const float hardCodedscriptTable2RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable2RpmBins, hardCodedscriptTable2RpmBins);
}

static void coupleBK2cannedscriptTable2LoadBins() {
	static const float hardCodedscriptTable2LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable2LoadBins, hardCodedscriptTable2LoadBins);
}

static void coupleBK2cannedscriptTable2() {
	static const float hardCodedscriptTable2[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->scriptTable2, hardCodedscriptTable2);
}

static void coupleBK2cannedscriptTable3RpmBins() {
	static const float hardCodedscriptTable3RpmBins[8] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable3RpmBins, hardCodedscriptTable3RpmBins);
}

static void coupleBK2cannedscriptTable3LoadBins() {
	static const float hardCodedscriptTable3LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable3LoadBins, hardCodedscriptTable3LoadBins);
}

static void coupleBK2cannedscriptTable3() {
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

static void coupleBK2cannedscriptTable4RpmBins() {
	static const float hardCodedscriptTable4RpmBins[10] = {650.0, 800.0, 1700.0, 2600.0, 3500.0, 4400.0, 5300.0, 7000.0, 0.0, 0.0};
	copyArray(config->scriptTable4RpmBins, hardCodedscriptTable4RpmBins);
}

static void coupleBK2cannedscriptTable4LoadBins() {
	static const float hardCodedscriptTable4LoadBins[8] = {20.0, 30.0, 50.0, 60.0, 80.0, 90.0, 110.0, 120.0};
	copyArray(config->scriptTable4LoadBins, hardCodedscriptTable4LoadBins);
}

static void coupleBK2cannedscriptTable4() {
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

static void coupleBK2cannedalsIgnRetardrpmBins() {
	static const float hardCodedalsIgnRetardrpmBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->alsIgnRetardrpmBins, hardCodedalsIgnRetardrpmBins);
}

static void coupleBK2cannedalsIgnRetardLoadBins() {
	static const float hardCodedalsIgnRetardLoadBins[4] = {2.0, 5.0, 7.0, 10.0};
	copyArray(config->alsIgnRetardLoadBins, hardCodedalsIgnRetardLoadBins);
}

static void coupleBK2cannedALSTimingRetardTable() {
	static const float hardCodedALSTimingRetardTable[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSTimingRetardTable, hardCodedALSTimingRetardTable);
}

static void coupleBK2cannedalsFuelAdjustmentrpmBins() {
	static const float hardCodedalsFuelAdjustmentrpmBins[4] = {650.0, 800.0, 3750.0, 7000.0};
	copyArray(config->alsFuelAdjustmentrpmBins, hardCodedalsFuelAdjustmentrpmBins);
}

static void coupleBK2cannedalsFuelAdjustmentLoadBins() {
	static const float hardCodedalsFuelAdjustmentLoadBins[4] = {2.0, 5.0, 7.0, 10.0};
	copyArray(config->alsFuelAdjustmentLoadBins, hardCodedalsFuelAdjustmentLoadBins);
}

static void coupleBK2cannedALSFuelAdjustment() {
	static const float hardCodedALSFuelAdjustment[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSFuelAdjustment, hardCodedALSFuelAdjustment);
}

static void coupleBK2cannedalsIgnSkiprpmBins() {
	static const float hardCodedalsIgnSkiprpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->alsIgnSkiprpmBins, hardCodedalsIgnSkiprpmBins);
}

static void coupleBK2cannedalsIgnSkipLoadBins() {
	static const float hardCodedalsIgnSkipLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->alsIgnSkipLoadBins, hardCodedalsIgnSkipLoadBins);
}

static void coupleBK2cannedALSIgnSkipTable() {
	static const float hardCodedALSIgnSkipTable[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->ALSIgnSkipTable, hardCodedALSIgnSkipTable);
}

static void coupleBK2cannedignitionRpmBins() {
	static const float hardCodedignitionRpmBins[16] = {650.0, 800.0, 1100.0, 1500.0, 2000.0, 2500.0, 3000.0, 3500.0, 4000.0, 4500.0, 5000.0, 5500.0, 6000.0, 6500.0, 7000.0, 8000.0};
	copyArray(config->ignitionRpmBins, hardCodedignitionRpmBins);
}

static void coupleBK2cannedignitionLoadBins() {
	static const float hardCodedignitionLoadBins[16] = {30.0, 35.0, 45.0, 55.0, 60.0, 75.0, 90.0, 100.0, 125.0, 150.0, 175.0, 200.0, 225.0, 250.0, 275.0, 300.0};
	copyArray(config->ignitionLoadBins, hardCodedignitionLoadBins);
}

static void coupleBK2cannedignitionTable() {
	static const float hardCodedignitionTable[16][16] = {
{12.100,	14.000,	17.800,	22.900,	29.300,	35.600,	-20.000,	-20.000,	-20.000,	-20.000,	-20.000,	-20.000,	42.000,	42.000,	42.000,	42.000,	},
{11.800,	13.700,	10.000,	14.900,	28.600,	34.800,	-20.000,	-20.000,	-20.000,	-20.000,	-20.000,	-20.000,	41.000,	41.000,	41.000,	41.000,	},
{11.600,	13.400,	12.300,	17.100,	28.000,	33.900,	39.200,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	},
{11.400,	13.200,	16.700,	21.400,	27.300,	33.100,	38.200,	39.000,	39.000,	39.000,	39.000,	39.000,	39.000,	39.000,	39.000,	39.000,	},
{11.200,	12.900,	16.300,	20.800,	26.600,	32.300,	37.200,	38.000,	38.000,	38.000,	38.000,	38.000,	38.000,	38.000,	38.000,	38.000,	},
{10.900,	12.600,	16.600,	20.200,	26.400,	26.700,	27.000,	28.500,	30.000,	30.400,	30.800,	31.100,	31.500,	31.900,	32.300,	33.000,	},
{10.800,	12.400,	16.800,	19.600,	23.900,	24.200,	24.500,	26.000,	27.500,	27.900,	28.300,	28.600,	29.000,	29.400,	29.800,	30.500,	},
{14.300,	14.900,	16.500,	18.800,	20.700,	21.700,	22.000,	23.500,	25.000,	25.400,	25.800,	26.100,	26.500,	26.900,	27.300,	28.000,	},
{14.000,	14.600,	15.600,	17.100,	18.500,	19.200,	19.500,	21.000,	22.500,	22.900,	23.300,	23.600,	24.000,	24.400,	24.800,	25.500,	},
{12.900,	13.300,	14.000,	15.100,	16.100,	16.700,	17.000,	18.500,	20.000,	20.400,	20.800,	21.100,	21.500,	21.900,	22.300,	23.000,	},
{11.700,	12.000,	12.400,	13.100,	13.700,	14.200,	14.500,	16.000,	17.500,	17.900,	18.300,	18.600,	19.000,	19.400,	19.800,	20.500,	},
{10.400,	10.500,	10.800,	11.100,	11.500,	11.900,	12.000,	13.500,	15.000,	15.400,	15.800,	16.100,	16.500,	16.900,	17.300,	18.000,	},
{8.800,	9.000,	9.100,	9.400,	9.700,	10.000,	10.300,	11.800,	13.300,	13.700,	14.100,	14.400,	14.800,	15.200,	15.600,	16.300,	},
{6.700,	6.800,	7.500,	7.700,	8.000,	8.400,	8.700,	10.200,	11.700,	12.100,	12.500,	12.800,	13.200,	13.600,	14.000,	14.700,	},
{1.800,	5.600,	6.200,	6.500,	6.800,	7.100,	7.000,	8.500,	10.000,	10.400,	10.800,	11.100,	11.500,	11.900,	12.300,	13.000,	},
{-1.200,	2.600,	3.200,	3.600,	4.100,	5.000,	7.100,	7.800,	8.400,	9.000,	9.400,	9.500,	9.700,	9.800,	10.000,	10.000,	},
};
	copyTable(config->ignitionTable, hardCodedignitionTable);
}

static void coupleBK2cannedignBlends1_rpmBins() {
	static const float hardCodedignBlends1_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_rpmBins, hardCodedignBlends1_rpmBins);
}

static void coupleBK2cannedignBlends1_loadBins() {
	static const float hardCodedignBlends1_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_loadBins, hardCodedignBlends1_loadBins);
}

static void coupleBK2cannedignBlends1_table() {
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

static void coupleBK2cannedignBlends2_rpmBins() {
	static const float hardCodedignBlends2_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_rpmBins, hardCodedignBlends2_rpmBins);
}

static void coupleBK2cannedignBlends2_loadBins() {
	static const float hardCodedignBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_loadBins, hardCodedignBlends2_loadBins);
}

static void coupleBK2cannedignBlends2_table() {
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

static void coupleBK2cannedignBlends3_table() {
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

static void coupleBK2cannedveBlends1_table() {
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

static void coupleBK2cannedveBlends2_loadBins() {
	static const float hardCodedveBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends2_loadBins, hardCodedveBlends2_loadBins);
}

static void coupleBK2cannedveBlends2_table() {
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

static void coupleBK2cannedveBlends3_rpmBins() {
	static const float hardCodedveBlends3_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_rpmBins, hardCodedveBlends3_rpmBins);
}

static void coupleBK2cannedveBlends3_loadBins() {
	static const float hardCodedveBlends3_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_loadBins, hardCodedveBlends3_loadBins);
}

static void coupleBK2cannedveBlends3_table() {
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

static void coupleBK2cannedboostOpenLoopBlends1_rpmBins() {
	static const float hardCodedboostOpenLoopBlends1_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostOpenLoopBlends1_rpmBins, hardCodedboostOpenLoopBlends1_rpmBins);
}

static void coupleBK2cannedboostClosedLoopBlends1_table() {
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

static void coupleBK2cannedboostClosedLoopBlends2_rpmBins() {
	static const float hardCodedboostClosedLoopBlends2_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_rpmBins, hardCodedboostClosedLoopBlends2_rpmBins);
}

static void coupleBK2cannedboostClosedLoopBlends2_loadBins() {
	static const float hardCodedboostClosedLoopBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.boostClosedLoopBlends2_loadBins, hardCodedboostClosedLoopBlends2_loadBins);
}

static void coupleBK2cannedboostClosedLoopBlends2_table() {
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

static void coupleBK2cannedignitionIatCorrTempBins() {
	static const float hardCodedignitionIatCorrTempBins[8] = {-40.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0};
	copyArray(config->ignitionIatCorrTempBins, hardCodedignitionIatCorrTempBins);
}

static void coupleBK2cannedignitionIatCorrLoadBins() {
	static const float hardCodedignitionIatCorrLoadBins[8] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0, 120.0, 140.0};
	copyArray(config->ignitionIatCorrLoadBins, hardCodedignitionIatCorrLoadBins);
}

static void coupleBK2cannedignitionIatCorrTable() {
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

static void coupleBK2cannedveRpmBins() {
	static const float hardCodedveRpmBins[16] = {600.0, 900.0, 1100.0, 1500.0, 1900.0, 2400.0, 3000.0, 3700.0, 4200.0, 4700.0, 5200.0, 5800.0, 6300.0, 6800.0, 7000.0, 7600.0};
	copyArray(config->veRpmBins, hardCodedveRpmBins);
}

static void coupleBK2cannedveLoadBins() {
	static const float hardCodedveLoadBins[16] = {30.0, 35.0, 45.0, 55.0, 60.0, 75.0, 90.0, 100.0, 125.0, 150.0, 175.0, 200.0, 225.0, 250.0, 275.0, 300.0};
	copyArray(config->veLoadBins, hardCodedveLoadBins);
}

static void coupleBK2cannedveTable() {
	static const float hardCodedveTable[16][16] = {
{52.000,	54.000,	54.000,	56.000,	61.000,	55.000,	55.000,	65.000,	65.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	60.000,	},
{51.500,	54.500,	54.400,	56.000,	61.000,	68.100,	66.800,	67.600,	68.200,	63.400,	63.400,	63.400,	63.400,	63.400,	63.400,	63.400,	},
{52.500,	55.400,	57.700,	62.200,	62.800,	65.800,	69.600,	71.100,	72.200,	67.600,	67.600,	67.600,	67.600,	67.600,	67.600,	67.600,	},
{54.200,	56.300,	59.000,	64.300,	65.700,	68.400,	71.400,	72.900,	73.900,	70.500,	70.400,	70.400,	70.300,	70.200,	70.200,	70.200,	},
{54.400,	56.700,	59.500,	65.200,	71.800,	75.400,	75.300,	73.800,	74.700,	72.600,	72.500,	72.300,	72.200,	72.100,	72.000,	72.000,	},
{55.100,	58.100,	61.400,	67.900,	75.400,	77.300,	75.000,	76.300,	77.200,	77.500,	77.000,	76.500,	76.000,	75.600,	75.400,	75.400,	},
{55.800,	59.400,	63.000,	70.100,	73.200,	75.400,	77.800,	78.900,	79.800,	79.100,	78.400,	77.700,	77.000,	76.400,	76.100,	76.100,	},
{56.000,	66.200,	70.600,	74.200,	74.100,	76.000,	79.900,	84.100,	82.200,	79.600,	78.900,	78.200,	77.500,	76.900,	76.600,	76.600,	},
{58.500,	67.400,	69.200,	75.500,	78.300,	79.900,	81.700,	83.700,	84.700,	82.100,	81.400,	80.700,	80.000,	79.400,	79.100,	79.100,	},
{52.900,	70.000,	71.900,	75.900,	79.800,	81.900,	83.700,	85.600,	86.100,	83.600,	83.000,	82.200,	81.600,	81.000,	80.700,	83.700,	},
{50.700,	71.000,	73.000,	77.300,	81.600,	83.900,	85.700,	87.600,	87.900,	85.400,	84.800,	84.000,	83.400,	82.800,	82.500,	85.500,	},
{53.700,	74.000,	76.000,	80.300,	84.600,	86.900,	88.700,	90.600,	90.900,	88.400,	87.800,	87.000,	86.400,	85.800,	85.500,	88.500,	},
{56.700,	77.000,	79.000,	83.300,	87.600,	89.900,	91.700,	93.600,	93.900,	91.400,	90.800,	90.000,	89.400,	88.800,	88.500,	91.500,	},
{59.700,	80.000,	82.000,	86.300,	90.600,	92.900,	94.700,	96.600,	96.900,	94.400,	93.800,	93.000,	92.400,	91.800,	91.500,	94.500,	},
{62.700,	83.000,	85.000,	89.300,	93.600,	95.900,	97.700,	99.600,	99.900,	97.400,	96.800,	96.000,	95.400,	94.800,	94.500,	97.500,	},
{65.700,	86.000,	88.000,	92.300,	96.600,	98.900,	100.700,	102.600,	102.900,	100.400,	99.800,	99.000,	98.400,	97.800,	97.500,	100.500,	},
};
	copyTable(config->veTable, hardCodedveTable);
}

static void coupleBK2cannedfuelTrimRpmBins() {
	static const float hardCodedfuelTrimRpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelTrimRpmBins, hardCodedfuelTrimRpmBins);
}

static void coupleBK2cannedfuelTrimLoadBins() {
	static const float hardCodedfuelTrimLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelTrimLoadBins, hardCodedfuelTrimLoadBins);
}

static void coupleBK2cannedfuelTrims1_table() {
	static const float hardCodedfuelTrims1_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims1_table, hardCodedfuelTrims1_table);
}

static void coupleBK2cannedfuelTrims2_table() {
	static const float hardCodedfuelTrims2_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims2_table, hardCodedfuelTrims2_table);
}

static void coupleBK2cannedfuelTrims3_table() {
	static const float hardCodedfuelTrims3_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims3_table, hardCodedfuelTrims3_table);
}

static void coupleBK2cannedfuelTrims4_table() {
	static const float hardCodedfuelTrims4_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims4_table, hardCodedfuelTrims4_table);
}

static void coupleBK2cannedfuelTrims5_table() {
	static const float hardCodedfuelTrims5_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims5_table, hardCodedfuelTrims5_table);
}

static void coupleBK2cannedfuelTrims6_table() {
	static const float hardCodedfuelTrims6_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims6_table, hardCodedfuelTrims6_table);
}

static void coupleBK2cannedfuelTrims7_table() {
	static const float hardCodedfuelTrims7_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims7_table, hardCodedfuelTrims7_table);
}

static void coupleBK2cannedfuelTrims8_table() {
	static const float hardCodedfuelTrims8_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims8_table, hardCodedfuelTrims8_table);
}

static void coupleBK2cannedfuelTrims9_table() {
	static const float hardCodedfuelTrims9_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims9_table, hardCodedfuelTrims9_table);
}

static void coupleBK2cannedfuelTrims10_table() {
	static const float hardCodedfuelTrims10_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims10_table, hardCodedfuelTrims10_table);
}

static void coupleBK2cannedfuelTrims11_table() {
	static const float hardCodedfuelTrims11_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims11_table, hardCodedfuelTrims11_table);
}

static void coupleBK2cannedfuelTrims12_table() {
	static const float hardCodedfuelTrims12_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->fuelTrims12.fuelTrims12_table, hardCodedfuelTrims12_table);
}

static void coupleBK2cannedignTrimRpmBins() {
	static const float hardCodedignTrimRpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->ignTrimRpmBins, hardCodedignTrimRpmBins);
}

static void coupleBK2cannedignTrimLoadBins() {
	static const float hardCodedignTrimLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->ignTrimLoadBins, hardCodedignTrimLoadBins);
}

static void coupleBK2cannedignTrims1_table() {
	static const float hardCodedignTrims1_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims1_table, hardCodedignTrims1_table);
}

static void coupleBK2cannedignTrims2_table() {
	static const float hardCodedignTrims2_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims2_table, hardCodedignTrims2_table);
}

static void coupleBK2cannedignTrims3_table() {
	static const float hardCodedignTrims3_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims3_table, hardCodedignTrims3_table);
}

static void coupleBK2cannedignTrims4_table() {
	static const float hardCodedignTrims4_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims4_table, hardCodedignTrims4_table);
}

static void coupleBK2cannedignTrims5_table() {
	static const float hardCodedignTrims5_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims5_table, hardCodedignTrims5_table);
}

static void coupleBK2cannedignTrims6_table() {
	static const float hardCodedignTrims6_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims6_table, hardCodedignTrims6_table);
}

static void coupleBK2cannedignTrims7_table() {
	static const float hardCodedignTrims7_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims7_table, hardCodedignTrims7_table);
}

static void coupleBK2cannedignTrims8_table() {
	static const float hardCodedignTrims8_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims8_table, hardCodedignTrims8_table);
}

static void coupleBK2cannedignTrims9_table() {
	static const float hardCodedignTrims9_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims9_table, hardCodedignTrims9_table);
}

static void coupleBK2cannedignTrims10_table() {
	static const float hardCodedignTrims10_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims10_table, hardCodedignTrims10_table);
}

static void coupleBK2cannedignTrims11_table() {
	static const float hardCodedignTrims11_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims11_table, hardCodedignTrims11_table);
}

static void coupleBK2cannedignTrims12_table() {
	static const float hardCodedignTrims12_table[4][4] = {
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->ignTrims12.ignTrims12_table, hardCodedignTrims12_table);
}

static void coupleBK2cannedmapEstimateRpmBins() {
	static const float hardCodedmapEstimateRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->mapEstimateRpmBins, hardCodedmapEstimateRpmBins);
}

static void coupleBK2cannedmapEstimateTpsBins() {
	static const float hardCodedmapEstimateTpsBins[16] = {0.0, 6.67, 13.33, 20.0, 26.67, 33.33, 40.0, 46.67, 53.33, 60.0, 66.67, 73.33, 80.0, 86.67, 93.33, 100.0};
	copyArray(config->mapEstimateTpsBins, hardCodedmapEstimateTpsBins);
}

static void coupleBK2cannedmapEstimateTable() {
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

static void coupleBK2cannedinjPhaseRpmBins() {
	static const float hardCodedinjPhaseRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->injPhaseRpmBins, hardCodedinjPhaseRpmBins);
}

static void coupleBK2cannedinjPhaseLoadBins() {
	static const float hardCodedinjPhaseLoadBins[16] = {10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 140.0, 150.0, 160.0};
	copyArray(config->injPhaseLoadBins, hardCodedinjPhaseLoadBins);
}

static void coupleBK2cannedinjectionPhase() {
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

static void coupleBK2cannedpedalToTpsRpmBins() {
	static const float hardCodedpedalToTpsRpmBins[8] = {0.0, 1100.0, 2300.0, 3400.0, 4600.0, 5700.0, 6900.0, 8000.0};
	copyArray(config->pedalToTpsRpmBins, hardCodedpedalToTpsRpmBins);
}

static void coupleBK2cannedpedalToTpsTable() {
	static const float hardCodedpedalToTpsTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{8.000,	8.000,	8.000,	8.000,	8.000,	8.000,	8.000,	8.000,	},
{17.000,	17.000,	17.000,	17.000,	17.000,	17.000,	17.000,	17.000,	},
{26.000,	26.000,	26.000,	26.000,	26.000,	26.000,	26.000,	26.000,	},
{34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	34.000,	},
{43.000,	43.000,	43.000,	43.000,	43.000,	43.000,	43.000,	43.000,	},
{86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	},
{100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	},
};
	copyTable(config->pedalToTpsTable, hardCodedpedalToTpsTable);
}

static void coupleBK2cannedthrottle2TrimRpmBins() {
	static const float hardCodedthrottle2TrimRpmBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->throttle2TrimRpmBins, hardCodedthrottle2TrimRpmBins);
}

static void coupleBK2cannedthrottle2TrimTpsBins() {
	static const float hardCodedthrottle2TrimTpsBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->throttle2TrimTpsBins, hardCodedthrottle2TrimTpsBins);
}

static void coupleBK2cannedthrottle2TrimTable() {
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

static void coupleBK2cannedmaxKnockRetardRpmBins() {
	static const float hardCodedmaxKnockRetardRpmBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->maxKnockRetardRpmBins, hardCodedmaxKnockRetardRpmBins);
}

static void coupleBK2cannedmaxKnockRetardLoadBins() {
	static const float hardCodedmaxKnockRetardLoadBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->maxKnockRetardLoadBins, hardCodedmaxKnockRetardLoadBins);
}

static void coupleBK2cannedmaxKnockRetardTable() {
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

static void coupleBK2cannedlambdaRpmBins() {
	static const float hardCodedlambdaRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->lambdaRpmBins, hardCodedlambdaRpmBins);
}

static void coupleBK2cannedlambdaLoadBins() {
	static const float hardCodedlambdaLoadBins[16] = {30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0, 120.0, 130.0, 150.0, 175.0, 200.0, 225.0, 250.0};
	copyArray(config->lambdaLoadBins, hardCodedlambdaLoadBins);
}

static void coupleBK2cannedlambdaTable() {
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

static void coupleBK2cannedhpfpTargetRpmBins() {
	static const float hardCodedhpfpTargetRpmBins[10] = {0.0, 900.0, 1800.0, 2650.0, 3550.0, 4450.0, 5350.0, 6200.0, 7100.0, 8000.0};
	copyArray(config->hpfpTargetRpmBins, hardCodedhpfpTargetRpmBins);
}

static void coupleBK2cannedhpfpTargetLoadBins() {
	static const float hardCodedhpfpTargetLoadBins[10] = {0.0, 20.0, 40.0, 60.0, 80.0, 100.0, 120.0, 140.0, 160.0, 180.0};
	copyArray(config->hpfpTargetLoadBins, hardCodedhpfpTargetLoadBins);
}

static void coupleBK2cannedhpfpCompensationRpmBins() {
	static const float hardCodedhpfpCompensationRpmBins[10] = {0.0, 900.0, 1800.0, 2650.0, 3550.0, 4450.0, 5350.0, 6200.0, 7100.0, 8000.0};
	copyArray(config->hpfpCompensationRpmBins, hardCodedhpfpCompensationRpmBins);
}

static void coupleBK2cannedhpfpCompensationLoadBins() {
	static const float hardCodedhpfpCompensationLoadBins[10] = {0.005, 0.018, 0.031, 0.043, 0.056, 0.069, 0.082, 0.094, 0.107, 0.12};
	copyArray(config->hpfpCompensationLoadBins, hardCodedhpfpCompensationLoadBins);
}

static void coupleBK2cannedhpfpCompensation() {
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

static void coupleBK2cannedpostCrankingFactor() {
	static const float hardCodedpostCrankingFactor[6][6] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->postCrankingFactor, hardCodedpostCrankingFactor);
}

static void coupleBK2cannedcrankingCycleBins() {
	static const float hardCodedcrankingCycleBins[8] = {1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0};
	copyArray(config->crankingCycleBins, hardCodedcrankingCycleBins);
}

```
