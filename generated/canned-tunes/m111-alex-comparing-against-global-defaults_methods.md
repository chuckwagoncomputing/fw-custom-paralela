```
static void cannedknockNoiseRpmBins() {
	static const float hardCodedknockNoiseRpmBins[16] = {650.0, 720.0, 790.0, 1160.0, 1580.0, 2000.0, 2420.0, 2840.0, 3260.0, 3680.0, 4100.0, 4520.0, 4940.0, 5413.0, 6207.0, 7000.0};
	copyArray(config->knockNoiseRpmBins, hardCodedknockNoiseRpmBins);
}

static void cannedknockBaseNoise() {
	static const float hardCodedknockBaseNoise[16] = {-39.0, -39.0, -39.0, -34.0, -27.0, -24.0, -23.0, -22.0, -20.0, -16.0, -13.0, -12.0, -10.0, -8.0, -6.0, -2.0};
	copyArray(config->knockBaseNoise, hardCodedknockBaseNoise);
}

static void cannedscriptCurve5Bins() {
	static const float hardCodedscriptCurve5Bins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->scriptCurve5Bins, hardCodedscriptCurve5Bins);
}

static void cannedscriptCurve6Bins() {
	static const float hardCodedscriptCurve6Bins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->scriptCurve6Bins, hardCodedscriptCurve6Bins);
}

static void cannedsparkDwellValues() {
	static const float hardCodedsparkDwellValues[8] = {4.0, 3.0, 3.0, 2.6, 2.6, 2.6, 2.6, 2.6};
	copyArray(config->sparkDwellValues, hardCodedsparkDwellValues);
}

static void canneddwellVoltageCorrVoltBins() {
	static const float hardCodeddwellVoltageCorrVoltBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->dwellVoltageCorrVoltBins, hardCodeddwellVoltageCorrVoltBins);
}

static void canneddwellVoltageCorrValues() {
	static const float hardCodeddwellVoltageCorrValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
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

static void cannedprimeBins() {
	static const float hardCodedprimeBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->primeBins, hardCodedprimeBins);
}

static void cannedprimeValues() {
	static const float hardCodedprimeValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->primeValues, hardCodedprimeValues);
}

static void cannedmap_samplingAngleBins() {
	static const float hardCodedmap_samplingAngleBins[8] = {800.0, 1686.0, 2571.0, 3457.0, 4343.0, 5229.0, 6114.0, 7000.0};
	copyArray(engineConfiguration->map.map_samplingAngleBins, hardCodedmap_samplingAngleBins);
}

static void cannedmap_samplingWindowBins() {
	static const float hardCodedmap_samplingWindowBins[8] = {800.0, 1686.0, 2571.0, 3457.0, 4343.0, 5229.0, 6114.0, 7000.0};
	copyArray(engineConfiguration->map.map_samplingWindowBins, hardCodedmap_samplingWindowBins);
}

static void cannedinjector_battLagCorrBins() {
	static const float hardCodedinjector_battLagCorrBins[8] = {6.0, 8.0, 10.0, 11.0, 12.0, 14.0, 16.0, 18.0};
	copyArray(engineConfiguration->injectorSecondary.injector_battLagCorrBins, hardCodedinjector_battLagCorrBins);
}

static void cannedinjector_battLagCorr() {
	static const float hardCodedinjector_battLagCorr[8] = {3.3710022, 2.84, 2.0, 1.8050001, 1.61, 1.37, 1.18, 1.04};
	copyArray(engineConfiguration->injectorSecondary.injector_battLagCorr, hardCodedinjector_battLagCorr);
}

static void cannedvrThreshold1_rpmBins() {
	static const float hardCodedvrThreshold1_rpmBins[6] = {600.0, 1000.0, 3500.0, 4500.0, 5500.0, 7000.0};
	copyArray(engineConfiguration->vrThreshold2.vrThreshold1_rpmBins, hardCodedvrThreshold1_rpmBins);
}

static void cannedvrThreshold1_values() {
	static const float hardCodedvrThreshold1_values[6] = {0.3, 1.2, 2.4, 2.43, 2.47, 2.5};
	copyArray(engineConfiguration->vrThreshold2.vrThreshold1_values, hardCodedvrThreshold1_values);
}

static void cannedvrThreshold2_rpmBins() {
	static const float hardCodedvrThreshold2_rpmBins[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->vrThreshold2.vrThreshold2_rpmBins, hardCodedvrThreshold2_rpmBins);
}

static void cannedvrThreshold2_values() {
	static const float hardCodedvrThreshold2_values[6] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->vrThreshold2.vrThreshold2_values, hardCodedvrThreshold2_values);
}

static void cannedmafDecodingBins() {
	static const float hardCodedmafDecodingBins[32] = {0.0, 18.013283, 26.451612, 34.677418, 42.903225, 51.129032, 59.35484, 67.580635, 75.80645, 84.03226, 92.258064, 100.48387, 108.70968, 116.935486, 125.16129, 133.3871, 141.6129, 149.83871, 158.06451, 166.29033, 174.51613, 182.74193, 190.96774, 199.19353, 207.41936, 215.64516, 223.87097, 232.09677, 240.3226, 248.54839, 256.7742, 265.0};
	copyArray(config->mafDecodingBins, hardCodedmafDecodingBins);
}

static void cannedmafDecoding() {
	static const float hardCodedmafDecoding[32] = {-34.5, 195.01631, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0, 200.0};
	copyArray(config->mafDecoding, hardCodedmafDecoding);
}

static void cannediatFuelCorrBins() {
	static const float hardCodediatFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 10.0, 20.0, 30.0, 40.0, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->iatFuelCorrBins, hardCodediatFuelCorrBins);
}

static void cannediatFuelCorr() {
	static const float hardCodediatFuelCorr[16] = {1.11, 1.07, 1.05, 1.02, 1.0, 0.98, 0.95, 0.93, 0.92, 0.9, 0.87, 0.85, 0.82, 0.8066667, 0.7933333, 0.78};
	copyArray(config->iatFuelCorr, hardCodediatFuelCorr);
}

static void cannedcltTimingBins() {
	static const float hardCodedcltTimingBins[8] = {-40.0, -15.0, 10.0, 20.0, 50.0, 80.0, 97.0, 120.0};
	copyArray(config->cltTimingBins, hardCodedcltTimingBins);
}

static void cannedcltTimingExtra() {
	static const float hardCodedcltTimingExtra[8] = {11.0, 9.0, 7.0, 5.0, 2.0, 0.0, 0.0, -2.0};
	copyArray(config->cltTimingExtra, hardCodedcltTimingExtra);
}

static void cannedcltFuelCorrBins() {
	static const float hardCodedcltFuelCorrBins[16] = {-40.0, -30.0, -20.0, -10.0, 0.0, 9.71, 21.46, 31.48, 41.17, 50.0, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->cltFuelCorrBins, hardCodedcltFuelCorrBins);
}

static void cannedcltFuelCorr() {
	static const float hardCodedcltFuelCorr[16] = {1.53, 1.53, 1.4499981, 1.3900006, 1.3099988, 1.25, 1.1900002, 1.1500002, 1.1000001, 1.06, 1.02, 1.0000021, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->cltFuelCorr, hardCodedcltFuelCorr);
}

static void cannedcrankingFuelBins() {
	static const float hardCodedcrankingFuelBins[8] = {-27.15, -3.94, 4.77, 20.0, 35.0, 50.0, 65.0, 90.0};
	copyArray(config->crankingFuelBins, hardCodedcrankingFuelBins);
}

static void cannedcrankingFuelCoef() {
	static const float hardCodedcrankingFuelCoef[8] = {3.0, 2.64, 2.13, 1.550003, 1.300003, 1.0999985, 1.0, 1.0};
	copyArray(config->crankingFuelCoef, hardCodedcrankingFuelCoef);
}

static void cannedcrankingFuelCoefE100() {
	static const float hardCodedcrankingFuelCoefE100[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->crankingFuelCoefE100, hardCodedcrankingFuelCoefE100);
}

static void cannedcltRevLimitRpmBins() {
	static const float hardCodedcltRevLimitRpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->cltRevLimitRpmBins, hardCodedcltRevLimitRpmBins);
}

static void cannedcltRevLimitRpm() {
	static const float hardCodedcltRevLimitRpm[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->cltRevLimitRpm, hardCodedcltRevLimitRpm);
}

static void cannedetbBiasBins() {
	static const float hardCodedetbBiasBins[8] = {0.0, 2.0, 4.0, 10.0, 30.0, 50.0, 80.0, 100.0};
	copyArray(config->etbBiasBins, hardCodedetbBiasBins);
}

static void cannedetbBiasValues() {
	static const float hardCodedetbBiasValues[8] = {-18.0, -18.0, -18.0, 16.0, 17.0, 15.0, 16.0, 22.0};
	copyArray(config->etbBiasValues, hardCodedetbBiasValues);
}

static void cannedcrankingCycleBins() {
	static const float hardCodedcrankingCycleBins[8] = {1.0, 2.0, 3.0, 4.0, 5.0, 6.0, 7.0, 8.0};
	copyArray(config->crankingCycleBins, hardCodedcrankingCycleBins);
}

static void cannedcrankingCycleCoef() {
	static const float hardCodedcrankingCycleCoef[8] = {2.0, 1.300003, 1.0, 1.0, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->crankingCycleCoef, hardCodedcrankingCycleCoef);
}

static void cannedcltIdleCorrBins() {
	static const float hardCodedcltIdleCorrBins[16] = {-40.0, -30.410034, -21.25, -9.919983, 0.11000013, 10.0, 20.0, 30.0, 39.779785, 50.52, 60.0, 70.0, 80.0, 90.0, 100.0, 110.0};
	copyArray(config->cltIdleCorrBins, hardCodedcltIdleCorrBins);
}

static void cannedcltIdleCorr() {
	static const float hardCodedcltIdleCorr[16] = {1.6900029, 1.5400014, 1.4800038, 1.4199986, 1.3700032, 1.3200002, 1.196672, 1.0933361, 1.059998, 1.0300001, 1.0000031, 0.99999666, 1.0, 1.0, 1.0, 1.0};
	copyArray(config->cltIdleCorr, hardCodedcltIdleCorr);
}

static void cannedcltCrankingCorrBins() {
	static const float hardCodedcltCrankingCorrBins[8] = {-40.0, -20.0, 0.0, 19.83, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->cltCrankingCorrBins, hardCodedcltCrankingCorrBins);
}

static void cannedcltCrankingCorr() {
	static const float hardCodedcltCrankingCorr[8] = {1.5, 1.3366667, 1.1733334, 1.05, 0.96000004, 0.8100002, 0.69000024, 0.6500002};
	copyArray(config->cltCrankingCorr, hardCodedcltCrankingCorr);
}

static void cannedcltIdleRpmBins() {
	static const float hardCodedcltIdleRpmBins[16] = {-40.0, -30.0, -20.0, 0.0, 22.0, 36.0, 46.0, 56.0, 60.0, 70.0, 80.0, 90.0, 100.0, 120.0, 130.0, 140.0};
	copyArray(config->cltIdleRpmBins, hardCodedcltIdleRpmBins);
}

static void cannedcltIdleRpm() {
	static const float hardCodedcltIdleRpm[16] = {1220.0, 1200.0, 1200.0, 1000.0, 1000.0, 960.0, 900.0, 860.0, 800.0, 800.0, 800.0, 800.0, 900.0, 480.0, 0.0, 0.0};
	copyArray(config->cltIdleRpm, hardCodedcltIdleRpm);
}

static void cannedfuelLevelBins() {
	static const float hardCodedfuelLevelBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelLevelBins, hardCodedfuelLevelBins);
}

static void cannedfuelLevelValues() {
	static const float hardCodedfuelLevelValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelLevelValues, hardCodedfuelLevelValues);
}

static void cannedwwCltBins() {
	static const float hardCodedwwCltBins[8] = {-40.0, -20.0, 0.0, 20.0, 40.0, 60.0, 80.0, 100.0};
	copyArray(config->wwCltBins, hardCodedwwCltBins);
}

static void cannedwwTauCltValues() {
	static const float hardCodedwwTauCltValues[8] = {0.95, 0.8, 0.67, 0.55, 0.4, 0.32, 0.25, 0.2};
	copyArray(config->wwTauCltValues, hardCodedwwTauCltValues);
}

static void cannedwwMapBins() {
	static const float hardCodedwwMapBins[8] = {7.0, 18.0, 29.0, 40.0, 49.0, 60.0, 70.0, 88.0};
	copyArray(config->wwMapBins, hardCodedwwMapBins);
}

static void cannedwwTauMapValues() {
	static const float hardCodedwwTauMapValues[8] = {0.76, 0.83, 0.84, 0.86, 0.87, 0.92, 0.94, 0.95};
	copyArray(config->wwTauMapValues, hardCodedwwTauMapValues);
}

static void cannedwwBetaCltValues() {
	static const float hardCodedwwBetaCltValues[8] = {0.79, 0.72, 0.63, 0.52, 0.44, 0.37, 0.3, 0.25};
	copyArray(config->wwBetaCltValues, hardCodedwwBetaCltValues);
}

static void cannedwwBetaMapValues() {
	static const float hardCodedwwBetaMapValues[8] = {0.05, 0.16, 0.25, 0.7, 0.78, 0.96, 1.05, 1.18};
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
	static const float hardCodedignBlends1_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_blendBins, hardCodedignBlends1_blendBins);
}

static void cannedignBlends2_blendBins() {
	static const float hardCodedignBlends2_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendBins, hardCodedignBlends2_blendBins);
}

static void cannedignBlends2_blendValues() {
	static const float hardCodedignBlends2_blendValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_blendValues, hardCodedignBlends2_blendValues);
}

static void cannedveBlends3_blendBins() {
	static const float hardCodedveBlends3_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_blendBins, hardCodedveBlends3_blendBins);
}

static void cannedveBlends4_blendBins() {
	static const float hardCodedveBlends4_blendBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends4_blendBins, hardCodedveBlends4_blendBins);
}

static void cannedveBlends4_blendValues() {
	static const float hardCodedveBlends4_blendValues[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
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
	static const float hardCodedtpsTpsAccelFromRpmBins[8] = {0.0, 5.0, 10.0, 20.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelFromRpmBins, hardCodedtpsTpsAccelFromRpmBins);
}

static void cannedtpsTpsAccelToRpmBins() {
	static const float hardCodedtpsTpsAccelToRpmBins[8] = {0.0, 5.0, 10.0, 20.0, 60.0, 70.0, 90.0, 100.0};
	copyArray(config->tpsTpsAccelToRpmBins, hardCodedtpsTpsAccelToRpmBins);
}

static void cannedtpsTpsAccelTable() {
	static const float hardCodedtpsTpsAccelTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{7.240,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{7.242,	2.880,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{11.927,	4.896,	2.500,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{14.515,	6.624,	4.250,	2.500,	0.000,	0.000,	0.000,	0.000,	},
{16.589,	8.064,	5.750,	4.250,	2.500,	0.000,	0.000,	0.000,	},
{18.144,	9.216,	7.000,	5.750,	4.250,	5.000,	0.000,	0.000,	},
{19.181,	10.080,	8.000,	7.000,	5.750,	8.500,	5.000,	0.000,	},
};
	copyTable(config->tpsTpsAccelTable, hardCodedtpsTpsAccelTable);
}

static void cannedtractionControlSlipBins() {
	static const float hardCodedtractionControlSlipBins[6] = {0.8, 0.9, 0.95, 1.05, 1.1, 1.2};
	copyArray(engineConfiguration->tractionControlSlipBins, hardCodedtractionControlSlipBins);
}

static void cannedboostRpmBins() {
	static const float hardCodedboostRpmBins[8] = {0.0, 1200.0, 2300.0, 3500.0, 4600.0, 5700.0, 6900.0, 8000.0};
	copyArray(config->boostRpmBins, hardCodedboostRpmBins);
}

static void cannedboostTpsBins() {
	static const float hardCodedboostTpsBins[8] = {0.0, 14.0, 28.0, 42.0, 58.0, 72.0, 86.0, 100.0};
	copyArray(config->boostTpsBins, hardCodedboostTpsBins);
}

static void cannedboostTableOpenLoop() {
	static const float hardCodedboostTableOpenLoop[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	},
{28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	},
{42.000,	42.000,	42.000,	42.000,	42.000,	42.000,	42.000,	42.000,	},
{58.000,	58.000,	58.000,	58.000,	58.000,	58.000,	58.000,	58.000,	},
{72.000,	72.000,	72.000,	72.000,	72.000,	72.000,	72.000,	72.000,	},
{86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	},
{100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	},
};
	copyTable(config->boostTableOpenLoop, hardCodedboostTableOpenLoop);
}

static void cannedboostTableClosedLoop() {
	static const float hardCodedboostTableClosedLoop[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	},
{28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	},
{42.000,	42.000,	42.000,	42.000,	42.000,	42.000,	42.000,	42.000,	},
{58.000,	58.000,	58.000,	58.000,	58.000,	58.000,	58.000,	58.000,	},
{72.000,	72.000,	72.000,	72.000,	72.000,	72.000,	72.000,	72.000,	},
{86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	},
{100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	},
};
	copyTable(config->boostTableClosedLoop, hardCodedboostTableClosedLoop);
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
	static const float hardCodedscriptTable1RpmBins[8] = {650.0, 800.0, 1100.0, 1500.0, 3500.0, 4400.0, 5300.0, 7000.0};
	copyArray(config->scriptTable1RpmBins, hardCodedscriptTable1RpmBins);
}

static void cannedscriptTable1LoadBins() {
	static const float hardCodedscriptTable1LoadBins[8] = {20.0, 25.0, 30.0, 40.0, 50.0, 70.0, 85.0, 100.0};
	copyArray(config->scriptTable1LoadBins, hardCodedscriptTable1LoadBins);
}

static void cannedscriptTable1() {
	static const float hardCodedscriptTable1[8][8] = {
{0.100,	0.100,	0.100,	0.100,	0.100,	0.100,	0.100,	0.100,	},
{0.100,	0.100,	0.100,	0.100,	0.100,	0.100,	0.100,	0.100,	},
{0.000,	0.200,	0.100,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.200,	0.050,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->scriptTable1, hardCodedscriptTable1);
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
	static const float hardCodedscriptTable4RpmBins[10] = {650.0, 859.0, 1353.0, 2000.0, 2700.0, 3400.0, 4100.0, 4856.0, 5777.0, 7000.0};
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
	static const float hardCodedignitionRpmBins[16] = {300.0, 700.0, 800.0, 900.0, 1100.0, 1400.0, 1700.0, 2100.0, 2500.0, 3000.0, 3500.0, 4000.0, 4500.0, 5000.0, 6500.0, 7000.0};
	copyArray(config->ignitionRpmBins, hardCodedignitionRpmBins);
}

static void cannedignitionLoadBins() {
	static const float hardCodedignitionLoadBins[16] = {30.0, 35.0, 40.0, 45.0, 50.0, 55.0, 60.0, 65.0, 70.0, 75.0, 80.0, 85.0, 90.0, 95.0, 100.0, 110.0};
	copyArray(config->ignitionLoadBins, hardCodedignitionLoadBins);
}

static void cannedignitionTable() {
	static const float hardCodedignitionTable[16][16] = {
{0.000,	8.000,	8.000,	8.000,	8.000,	10.000,	18.400,	22.800,	23.700,	30.700,	30.700,	30.700,	30.700,	30.700,	30.700,	30.700,	},
{0.000,	8.000,	8.000,	8.000,	8.000,	11.500,	19.700,	24.000,	25.000,	30.500,	30.500,	30.500,	30.500,	30.500,	30.500,	30.500,	},
{0.000,	8.000,	8.000,	8.000,	8.000,	13.000,	21.000,	25.100,	26.300,	30.200,	30.200,	30.200,	30.200,	30.200,	30.200,	30.200,	},
{0.000,	8.000,	8.000,	8.000,	8.000,	14.500,	22.300,	26.300,	27.500,	30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	},
{0.000,	8.000,	8.000,	8.000,	8.000,	16.000,	23.600,	27.400,	28.800,	29.800,	29.800,	29.800,	29.800,	29.800,	29.800,	29.800,	},
{0.000,	8.000,	8.000,	8.000,	8.000,	16.000,	23.400,	27.200,	28.500,	29.500,	29.500,	29.500,	29.500,	29.500,	29.500,	29.500,	},
{0.000,	8.000,	8.000,	8.000,	8.000,	16.000,	23.200,	26.900,	28.200,	29.200,	29.200,	29.200,	29.200,	29.200,	29.200,	29.200,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	16.000,	23.100,	26.600,	28.000,	28.900,	28.900,	28.900,	28.900,	28.900,	28.900,	28.900,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	16.000,	23.000,	26.200,	27.600,	28.500,	28.500,	28.500,	28.500,	28.500,	28.500,	28.500,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	16.000,	22.500,	25.700,	27.000,	28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	28.000,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	16.000,	22.000,	25.100,	26.500,	27.400,	27.400,	27.400,	27.400,	27.400,	27.400,	27.400,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	15.900,	21.500,	24.600,	26.000,	27.000,	27.000,	27.000,	27.000,	27.000,	27.000,	27.000,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	15.800,	21.000,	24.200,	25.500,	26.500,	26.500,	26.500,	26.500,	26.500,	26.500,	26.500,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	15.100,	20.000,	23.100,	25.300,	25.800,	25.800,	25.800,	25.800,	25.800,	25.800,	25.800,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	14.400,	19.000,	21.900,	25.100,	25.100,	25.100,	25.100,	25.100,	25.100,	25.100,	25.100,	},
{0.000,	10.000,	10.000,	10.000,	10.000,	13.200,	16.500,	19.100,	22.000,	23.700,	23.700,	23.700,	23.700,	23.700,	23.700,	23.700,	},
};
	copyTable(config->ignitionTable, hardCodedignitionTable);
}

static void cannedignBlends1_rpmBins() {
	static const float hardCodedignBlends1_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends1_rpmBins, hardCodedignBlends1_rpmBins);
}

static void cannedignBlends1_loadBins() {
	static const float hardCodedignBlends1_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
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
	static const float hardCodedignBlends2_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.ignBlends2_rpmBins, hardCodedignBlends2_rpmBins);
}

static void cannedignBlends2_loadBins() {
	static const float hardCodedignBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
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

static void cannedveBlends2_loadBins() {
	static const float hardCodedveBlends2_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
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
	static const float hardCodedveBlends3_rpmBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(engineConfiguration->boostClosedLoopBlends2.veBlends3_rpmBins, hardCodedveBlends3_rpmBins);
}

static void cannedveBlends3_loadBins() {
	static const float hardCodedveBlends3_loadBins[8] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
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
	static const float hardCodedignitionIatCorrLoadBins[8] = {0.0, 5.0, 10.0, 25.0, 45.0, 65.0, 90.0, 110.0};
	copyArray(config->ignitionIatCorrLoadBins, hardCodedignitionIatCorrLoadBins);
}

static void cannedignitionIatCorrTable() {
	static const float hardCodedignitionIatCorrTable[8][8] = {
{4.000,	4.000,	4.000,	4.000,	4.000,	4.000,	4.000,	4.000,	},
{2.900,	2.900,	2.900,	2.900,	2.900,	2.900,	2.900,	2.900,	},
{0.700,	0.700,	0.700,	0.700,	0.700,	0.700,	0.700,	0.700,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{-0.600,	-0.600,	-0.600,	-0.600,	-0.600,	-0.600,	-0.600,	-0.600,	},
{-3.400,	-3.400,	-3.400,	-3.400,	-3.400,	-3.400,	-3.400,	-3.400,	},
{-4.000,	-4.000,	-4.000,	-4.000,	-4.000,	-4.000,	-4.000,	-4.000,	},
{-6.000,	-6.000,	-6.000,	-6.000,	-6.000,	-6.000,	-6.000,	-6.000,	},
};
	copyTable(config->ignitionIatCorrTable, hardCodedignitionIatCorrTable);
}

static void cannedveRpmBins() {
	static const float hardCodedveRpmBins[16] = {650.0, 800.0, 1000.0, 1200.0, 1500.0, 2000.0, 2500.0, 3000.0, 3500.0, 4000.0, 4500.0, 5000.0, 5500.0, 6000.0, 6500.0, 7000.0};
	copyArray(config->veRpmBins, hardCodedveRpmBins);
}

static void cannedveLoadBins() {
	static const float hardCodedveLoadBins[16] = {15.0, 25.0, 30.0, 35.0, 40.0, 45.0, 50.0, 55.0, 65.0, 70.0, 75.0, 80.0, 85.0, 90.0, 95.0, 100.0};
	copyArray(config->veLoadBins, hardCodedveLoadBins);
}

static void cannedveTable() {
	static const float hardCodedveTable[16][16] = {
{27.800,	27.500,	17.300,	7.800,	5.400,	6.500,	7.200,	10.300,	11.600,	13.700,	27.600,	30.000,	23.400,	23.800,	25.700,	34.400,	},
{27.800,	27.500,	17.300,	7.800,	5.400,	6.500,	7.200,	10.300,	11.600,	13.700,	27.600,	30.000,	23.400,	23.800,	25.700,	34.400,	},
{21.200,	22.400,	22.900,	12.800,	12.300,	12.600,	13.700,	13.800,	13.100,	28.800,	29.600,	32.400,	31.500,	32.300,	33.500,	34.400,	},
{27.400,	27.300,	28.100,	28.200,	29.500,	32.000,	37.800,	26.700,	24.000,	37.800,	39.000,	40.100,	45.000,	46.800,	48.000,	49.000,	},
{32.600,	33.900,	34.200,	39.900,	40.900,	43.200,	43.100,	39.600,	34.900,	40.600,	43.300,	47.300,	47.900,	49.700,	50.600,	51.500,	},
{38.000,	40.500,	46.600,	50.600,	50.400,	51.400,	50.800,	47.300,	44.400,	48.200,	51.800,	52.200,	49.900,	51.700,	52.400,	53.300,	},
{44.400,	47.900,	49.200,	60.200,	55.800,	58.600,	59.000,	53.700,	50.600,	49.400,	48.800,	50.600,	52.300,	54.000,	55.500,	57.100,	},
{41.400,	57.800,	66.200,	65.800,	65.500,	64.900,	63.200,	60.700,	59.100,	60.600,	61.300,	55.200,	55.500,	57.200,	58.900,	60.700,	},
{65.000,	68.700,	69.100,	70.000,	70.600,	71.600,	68.900,	66.900,	64.900,	69.600,	63.000,	64.400,	61.900,	63.500,	65.700,	67.900,	},
{69.000,	76.500,	74.000,	75.600,	73.600,	74.200,	72.500,	69.700,	68.600,	70.300,	65.100,	66.300,	63.300,	64.400,	66.400,	68.500,	},
{73.000,	84.200,	78.800,	81.200,	76.600,	76.800,	76.000,	72.500,	72.200,	70.900,	67.100,	68.100,	64.600,	65.300,	67.100,	69.100,	},
{74.200,	84.400,	78.800,	82.400,	77.900,	78.900,	78.100,	75.000,	75.600,	75.700,	75.200,	77.200,	73.500,	69.800,	70.500,	71.500,	},
{75.400,	84.500,	78.800,	83.600,	79.100,	81.000,	80.200,	77.500,	78.900,	80.500,	83.300,	86.300,	82.300,	74.200,	73.900,	73.900,	},
{76.900,	84.700,	78.800,	81.900,	80.000,	81.500,	81.600,	78.700,	80.700,	83.400,	86.500,	90.200,	89.500,	82.800,	82.700,	82.700,	},
{78.300,	84.800,	78.800,	80.200,	80.900,	82.000,	82.900,	79.900,	82.400,	86.200,	89.600,	94.000,	96.600,	91.400,	91.500,	91.500,	},
{80.000,	85.000,	84.900,	84.800,	84.700,	84.400,	84.200,	83.900,	83.700,	85.900,	89.100,	91.500,	91.600,	90.300,	92.000,	92.000,	},
};
	copyTable(config->veTable, hardCodedveTable);
}

static void cannedfuelTrimRpmBins() {
	static const float hardCodedfuelTrimRpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->fuelTrimRpmBins, hardCodedfuelTrimRpmBins);
}

static void cannedfuelTrimLoadBins() {
	static const float hardCodedfuelTrimLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
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
	static const float hardCodedignTrimRpmBins[4] = {0.0, 0.0, 0.0, 0.0};
	copyArray(config->ignTrimRpmBins, hardCodedignTrimRpmBins);
}

static void cannedignTrimLoadBins() {
	static const float hardCodedignTrimLoadBins[4] = {0.0, 0.0, 0.0, 0.0};
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
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
{-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	-360.000,	},
};
	copyTable(config->injectionPhase, hardCodedinjectionPhase);
}

static void cannedpedalToTpsRpmBins() {
	static const float hardCodedpedalToTpsRpmBins[8] = {0.0, 600.0, 800.0, 1000.0, 1500.0, 2000.0, 4000.0, 8000.0};
	copyArray(config->pedalToTpsRpmBins, hardCodedpedalToTpsRpmBins);
}

static void cannedpedalToTpsPedalBins() {
	static const float hardCodedpedalToTpsPedalBins[8] = {0.0, 10.0, 15.0, 20.0, 35.0, 71.0, 86.0, 100.0};
	copyArray(config->pedalToTpsPedalBins, hardCodedpedalToTpsPedalBins);
}

static void cannedpedalToTpsTable() {
	static const float hardCodedpedalToTpsTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{2.000,	3.000,	2.000,	4.000,	4.000,	4.000,	4.000,	10.000,	},
{4.000,	4.000,	4.000,	5.000,	7.000,	14.000,	15.000,	15.000,	},
{8.000,	8.000,	8.000,	9.000,	12.000,	20.000,	20.000,	20.000,	},
{15.000,	15.000,	18.000,	20.000,	29.000,	33.000,	35.000,	35.000,	},
{40.000,	40.000,	40.000,	50.000,	60.000,	65.000,	71.000,	71.000,	},
{86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	86.000,	},
{100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	100.000,	},
};
	copyTable(config->pedalToTpsTable, hardCodedpedalToTpsTable);
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
	static const float hardCodedmaxKnockRetardRpmBins[6] = {500.0, 2000.0, 3000.0, 4000.0, 6000.0, 7000.0};
	copyArray(config->maxKnockRetardRpmBins, hardCodedmaxKnockRetardRpmBins);
}

static void cannedmaxKnockRetardLoadBins() {
	static const float hardCodedmaxKnockRetardLoadBins[6] = {0.0, 20.0, 50.0, 70.0, 90.0, 100.0};
	copyArray(config->maxKnockRetardLoadBins, hardCodedmaxKnockRetardLoadBins);
}

static void cannedmaxKnockRetardTable() {
	static const float hardCodedmaxKnockRetardTable[6][6] = {
{2.000,	2.000,	2.000,	2.000,	2.000,	2.000,	},
{2.000,	2.000,	2.000,	2.000,	2.000,	2.000,	},
{3.250,	3.250,	3.250,	3.250,	3.250,	3.250,	},
{4.250,	4.250,	4.250,	4.250,	4.250,	4.250,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
{5.000,	5.000,	5.000,	5.000,	5.000,	5.000,	},
};
	copyTable(config->maxKnockRetardTable, hardCodedmaxKnockRetardTable);
}

static void cannedlambdaRpmBins() {
	static const float hardCodedlambdaRpmBins[16] = {650.0, 800.0, 1100.0, 1400.0, 1700.0, 2000.0, 2300.0, 2600.0, 2900.0, 3200.0, 3500.0, 3800.0, 4100.0, 4400.0, 4700.0, 7000.0};
	copyArray(config->lambdaRpmBins, hardCodedlambdaRpmBins);
}

static void cannedlambdaLoadBins() {
	static const float hardCodedlambdaLoadBins[16] = {10.0, 20.0, 25.0, 30.0, 32.0, 40.0, 45.0, 50.0, 55.0, 60.0, 65.0, 70.0, 80.0, 85.0, 90.0, 100.0};
	copyArray(config->lambdaLoadBins, hardCodedlambdaLoadBins);
}

static void cannedlambdaTable() {
	static const float hardCodedlambdaTable[16][16] = {
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.200,	14.200,	14.200,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.200,	14.200,	14.200,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.200,	14.200,	14.200,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.200,	14.200,	14.200,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.200,	14.200,	14.200,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.200,	14.000,	14.000,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.000,	14.000,	},
{14.000,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.000,	14.000,	},
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.000,	14.000,	},
{14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.200,	14.000,	14.000,	},
{14.500,	14.500,	14.500,	14.500,	14.500,	14.500,	14.500,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.000,	14.000,	14.000,	},
{14.500,	14.500,	14.500,	14.500,	14.500,	14.500,	14.500,	14.700,	14.700,	14.700,	14.700,	14.700,	14.700,	14.000,	14.000,	14.000,	},
{14.200,	14.200,	14.200,	14.300,	14.300,	14.300,	14.300,	14.300,	14.700,	14.700,	14.700,	14.700,	14.700,	14.300,	14.300,	14.300,	},
{14.200,	14.200,	14.200,	14.200,	14.200,	14.200,	14.200,	14.200,	14.400,	14.400,	14.400,	14.400,	14.400,	14.200,	14.200,	14.200,	},
{14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	14.000,	},
{13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	13.900,	},
};
	copyTable(config->lambdaTable, hardCodedlambdaTable);
}

static void cannediacPidMultRpmBins() {
	static const float hardCodediacPidMultRpmBins[8] = {600.0, 800.0, 900.0, 1000.0, 1100.0, 1200.0, 1300.0, 1500.0};
	copyArray(config->iacPidMultRpmBins, hardCodediacPidMultRpmBins);
}

static void cannediacPidMultLoadBins() {
	static const float hardCodediacPidMultLoadBins[8] = {10.0, 20.0, 30.0, 35.0, 40.0, 50.0, 70.0, 100.0};
	copyArray(config->iacPidMultLoadBins, hardCodediacPidMultLoadBins);
}

static void cannediacPidMultTable() {
	static const float hardCodediacPidMultTable[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{6.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{8.000,	6.000,	4.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{9.000,	8.000,	4.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{10.000,	10.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(config->iacPidMultTable, hardCodediacPidMultTable);
}

static void cannedgppwm1_loadBins() {
	static const float hardCodedgppwm1_loadBins[8] = {0.0, 14.0, 70.0, 80.0, 82.0, 90.0, 92.0, 100.0};
	copyArray(engineConfiguration->gppwm4.gppwm1_loadBins, hardCodedgppwm1_loadBins);
}

static void cannedgppwm1_table() {
	static const float hardCodedgppwm1_table[8][8] = {
{90.000,	90.000,	90.000,	90.000,	90.000,	90.000,	90.000,	90.000,	},
{90.000,	90.000,	90.000,	90.000,	90.000,	90.000,	90.000,	90.000,	},
{85.000,	40.000,	40.000,	60.000,	85.000,	85.000,	85.000,	85.000,	},
{50.000,	40.000,	40.000,	50.000,	80.000,	80.000,	80.000,	80.000,	},
{40.000,	40.000,	40.000,	40.000,	60.000,	60.000,	60.000,	60.000,	},
{40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	40.000,	},
{30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	},
{30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	30.000,	},
};
	copyTable(engineConfiguration->gppwm4.gppwm1_table, hardCodedgppwm1_table);
}

static void cannedgppwm2_rpmBins() {
	static const float hardCodedgppwm2_rpmBins[8] = {1000.0, 1900.0, 2100.0, 3000.0, 4000.0, 4900.0, 5100.0, 7000.0};
	copyArray(engineConfiguration->gppwm4.gppwm2_rpmBins, hardCodedgppwm2_rpmBins);
}

static void cannedgppwm2_table() {
	static const float hardCodedgppwm2_table[8][8] = {
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	0.000,	0.000,	},
{0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	0.000,	0.000,	},
{0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	0.000,	0.000,	},
{0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	0.000,	0.000,	},
{0.000,	0.000,	100.000,	100.000,	100.000,	100.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->gppwm4.gppwm2_table, hardCodedgppwm2_table);
}

static void cannedgppwm3_table() {
	static const float hardCodedgppwm3_table[8][8] = {
{5.000,	5.000,	0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{5.000,	5.000,	0.000,	0.000,	0.000,	0.000,	14.000,	14.000,	},
{70.000,	70.000,	0.000,	0.000,	0.000,	0.000,	28.000,	28.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	42.000,	42.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	57.000,	57.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	71.000,	71.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	85.000,	85.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	100.000,	100.000,	},
};
	copyTable(engineConfiguration->gppwm4.gppwm3_table, hardCodedgppwm3_table);
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
	static const float hardCodedhpfpTargetRpmBins[10] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->hpfpTargetRpmBins, hardCodedhpfpTargetRpmBins);
}

static void cannedhpfpTargetLoadBins() {
	static const float hardCodedhpfpTargetLoadBins[10] = {0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0, 0.0};
	copyArray(config->hpfpTargetLoadBins, hardCodedhpfpTargetLoadBins);
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

static void cannedpostCrankingFactor() {
	static const float hardCodedpostCrankingFactor[6][6] = {
{1.200,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
{0.000,	0.000,	0.000,	0.000,	0.000,	0.000,	},
};
	copyTable(engineConfiguration->postCrankingFactor, hardCodedpostCrankingFactor);
}

```
