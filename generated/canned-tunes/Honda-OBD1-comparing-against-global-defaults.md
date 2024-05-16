# Honda-OBD1-comparing-against-global-defaults

// canned tune https://rusefi.com/online/view.php?msq=1621

```
    // default 1.65
    engineConfiguration->displacement = 1.493;
    // default "60-2"
    engineConfiguration->trigger.type = TT_TOOTHED_WHEEL;
    // default 0.0
    engineConfiguration->trigger.customTotalToothCount = 24;
    // default "On crankshaft"
    engineConfiguration->skippedWheelOnCam = On camshaft;
    // default 0.0
    engineConfiguration->globalTriggerAngleOffset = 80;
    // default 450.0
    engineConfiguration->vvtOffsets[0] = 0;
    // default 200.0
    engineConfiguration->injector.flow = 240;
    // default "None"
    engineConfiguration->injectorCompensationMode = ICM_FixedRailPressure;
    // default 300.0
    engineConfiguration->fuelReferencePressure = 294;
    // default 0.0
    engineConfiguration->cylinderBankSelect[0] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[1] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[2] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[3] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[4] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[5] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[6] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[7] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[8] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[9] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[10] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[11] = 1;
    // default "GPPWM Output 3"
    engineConfiguration->ignBlends[0].blendParameter = GPPWM_Zero;
    // default "VVT 1 I"
    engineConfiguration->ignBlends[0].yAxisOverride = GPPWM_Zero;
    // default "Aux Linear 1"
    engineConfiguration->veBlends[2].blendParameter = GPPWM_Zero;
    // default "IAT"
    engineConfiguration->boostOpenLoopBlends[0].blendParameter = GPPWM_Zero;
    // default "Aux Temp 2"
    engineConfiguration->boostClosedLoopBlends[1].blendParameter = GPPWM_Zero;
    // default "CLT"
    engineConfiguration->boostClosedLoopBlends[1].yAxisOverride = GPPWM_Zero;
    // default 0.0
    engineConfiguration->tpsMin = 124;
    // default 1000.0
    engineConfiguration->tpsMax = 919;
    // default "Normal"
    engineConfiguration->clutchDownPinInverted = false;
    // default "Normal"
    engineConfiguration->clutchUpPinInverted = false;
    // default "Normal"
    engineConfiguration->flexSensorInverted = false;
    // default 0.0
    engineConfiguration->mapLowValueVoltage = 2.91;
    // default 410.0
    engineConfiguration->mapErrorDetectionTooHigh = 250;
    // default "false"
    engineConfiguration->enableAemXSeries = true;
    // default 50.0
    engineConfiguration->manIdlePosition = 29;
    // default 2.0
    engineConfiguration->fan1ExtraIdle = 10;
    // default 92.0
    engineConfiguration->fanOnTemperature = 95;
    // default 88.0
    engineConfiguration->fanOffTemperature = 91;
    // default "false"
    engineConfiguration->enableSoftwareKnock = true;
    // default "false"
    engineConfiguration->enableVerboseCanTx = true;
    // default 200.0
    engineConfiguration->rpmSoftLimitWindowSize = 0;
    // default 4.0
    engineConfiguration->rpmSoftLimitTimingRetard = 0;
    // default 1.0
    engineConfiguration->tpsAccelFractionDivisor = 0;
    // default "Throttle 1"
    engineConfiguration->etbFunctions[0] = DC_None;
    // default "Throttle 2"
    engineConfiguration->etbFunctions[1] = DC_None;
    // default 250.0
    engineConfiguration->gppwm[0].pwmFrequency = 0;
    // default 60.0
    engineConfiguration->gppwm[0].onAboveDuty = 80;
    // default 50.0
    engineConfiguration->gppwm[0].offBelowDuty = 10;
    // default "Zero"
    engineConfiguration->gppwm[0].loadAxis = GPPWM_Map;


	cannedknockNoiseRpmBins();
	cannedknockBaseNoise();
	canneddwellVoltageCorrVoltBins();
	canneddwellVoltageCorrValues();
	cannedtpsTspCorrValuesBins();
	cannedtpsTspCorrValues();
	cannedinjector_battLagCorrBins();
	cannedinjector_battLagCorr();
	cannedmafDecodingBins();
	cannedmafDecoding();
	cannediatFuelCorrBins();
	cannediatFuelCorr();
	cannedcltFuelCorrBins();
	cannedcltFuelCorr();
	cannedcrankingFuelBins();
	cannedcrankingFuelCoef();
	cannedcrankingFuelCoefE100();
	cannedcltRevLimitRpmBins();
	cannedcltRevLimitRpm();
	cannedcrankingCycleBins();
	cannedcrankingCycleCoef();
	cannedcltIdleCorrBins();
	cannedcltIdleCorr();
	cannedfuelLevelBins();
	cannedfuelLevelValues();
	cannedhpfpLobeProfileQuantityBins();
	cannedhpfpLobeProfileAngle();
	cannedhpfpDeadtimeVoltsBins();
	cannedwwCltBins();
	cannedwwTauCltValues();
	cannedwwMapBins();
	cannedwwTauMapValues();
	cannedwwBetaCltValues();
	cannedwwBetaMapValues();
	cannedtcu_tccTpsBins();
	cannedtcu_tccLockSpeed();
	cannedtcu_tccUnlockSpeed();
	cannedtcu_pcAirmassBins();
	cannedtcu_pcValsR();
	cannedtcu_pcValsN();
	cannedtcu_pcVals1();
	cannedtcu_pcVals2();
	cannedtcu_pcVals3();
	cannedtcu_pcVals4();
	cannedtcu_pcVals12();
	cannedtcu_pcVals23();
	cannedtcu_pcVals34();
	cannedtcu_pcVals21();
	cannedtcu_pcVals32();
	cannedtcu_pcVals43();
	cannedtcu_32SpeedBins();
	cannedtcu_32Vals();
	cannedtcu_rangeM();
	cannedtcu_rangeM3();
	cannedtcu_rangeM2();
	cannedtcu_rangeM1();
	cannedignBlends1_blendBins();
	cannedignBlends1_blendValues();
	cannedignBlends2_blendBins();
	cannedignBlends2_blendValues();
	cannedignBlends3_blendBins();
	cannedignBlends3_blendValues();
	cannedignBlends4_blendBins();
	cannedignBlends4_blendValues();
	cannedveBlends1_blendBins();
	cannedveBlends1_blendValues();
	cannedveBlends2_blendBins();
	cannedveBlends2_blendValues();
	cannedveBlends3_blendBins();
	cannedveBlends3_blendValues();
	cannedveBlends4_blendBins();
	cannedveBlends4_blendValues();
	cannedboostOpenLoopBlends1_blendBins();
	cannedboostClosedLoopBlends2_blendBins();
	cannedthrottleEstimateEffectiveAreaBins();
	cannedtpsTpsAccelFromRpmBins();
	cannedtpsTpsAccelToRpmBins();
	cannedtpsTpsAccelTable();
	cannedtractionControlSlipBins();
	cannedboostTableOpenLoop();
	cannedvvtTable1RpmBins();
	cannedvvtTable1LoadBins();
	cannedvvtTable1();
	cannedvvtTable2RpmBins();
	cannedvvtTable2LoadBins();
	cannedvvtTable2();
	cannedscriptTable1RpmBins();
	cannedscriptTable1LoadBins();
	cannedscriptTable2RpmBins();
	cannedscriptTable2LoadBins();
	cannedscriptTable3RpmBins();
	cannedscriptTable3LoadBins();
	cannedscriptTable3();
	cannedscriptTable4RpmBins();
	cannedscriptTable4LoadBins();
	cannedscriptTable4();
	cannedalsIgnRetardrpmBins();
	cannedalsIgnRetardLoadBins();
	cannedALSTimingRetardTable();
	cannedalsFuelAdjustmentrpmBins();
	cannedalsFuelAdjustmentLoadBins();
	cannedALSFuelAdjustment();
	cannedalsIgnSkiprpmBins();
	cannedalsIgnSkipLoadBins();
	cannedALSIgnSkipTable();
	cannedignitionRpmBins();
	cannedignitionLoadBins();
	cannedignitionTable();
	cannedignBlends1_rpmBins();
	cannedignBlends1_loadBins();
	cannedignBlends1_table();
	cannedignBlends2_rpmBins();
	cannedignBlends2_loadBins();
	cannedignBlends2_table();
	cannedignBlends3_rpmBins();
	cannedignBlends3_loadBins();
	cannedignBlends3_table();
	cannedignBlends4_rpmBins();
	cannedignBlends4_loadBins();
	cannedveBlends1_rpmBins();
	cannedveBlends1_loadBins();
	cannedveBlends1_table();
	cannedveBlends2_rpmBins();
	cannedveBlends2_loadBins();
	cannedveBlends2_table();
	cannedveBlends3_rpmBins();
	cannedveBlends3_loadBins();
	cannedveBlends3_table();
	cannedveBlends4_rpmBins();
	cannedveBlends4_loadBins();
	cannedboostOpenLoopBlends1_rpmBins();
	cannedboostClosedLoopBlends1_table();
	cannedboostClosedLoopBlends2_rpmBins();
	cannedboostClosedLoopBlends2_loadBins();
	cannedboostClosedLoopBlends2_table();
	cannedignitionIatCorrTempBins();
	cannedignitionIatCorrLoadBins();
	cannedignitionIatCorrTable();
	cannedveRpmBins();
	cannedveLoadBins();
	cannedveTable();
	cannedfuelTrimRpmBins();
	cannedfuelTrimLoadBins();
	cannedfuelTrims1_table();
	cannedfuelTrims2_table();
	cannedfuelTrims3_table();
	cannedfuelTrims4_table();
	cannedfuelTrims5_table();
	cannedfuelTrims6_table();
	cannedfuelTrims7_table();
	cannedfuelTrims8_table();
	cannedfuelTrims9_table();
	cannedfuelTrims10_table();
	cannedfuelTrims11_table();
	cannedfuelTrims12_table();
	cannedignTrimRpmBins();
	cannedignTrimLoadBins();
	cannedignTrims1_table();
	cannedignTrims2_table();
	cannedignTrims3_table();
	cannedignTrims4_table();
	cannedignTrims5_table();
	cannedignTrims6_table();
	cannedignTrims7_table();
	cannedignTrims8_table();
	cannedignTrims9_table();
	cannedignTrims10_table();
	cannedignTrims11_table();
	cannedignTrims12_table();
	cannedmapEstimateRpmBins();
	cannedmapEstimateTpsBins();
	cannedmapEstimateTable();
	cannedinjPhaseRpmBins();
	cannedinjPhaseLoadBins();
	cannedinjectionPhase();
	cannedthrottle2TrimRpmBins();
	cannedthrottle2TrimTpsBins();
	cannedthrottle2TrimTable();
	cannedmaxKnockRetardRpmBins();
	cannedmaxKnockRetardLoadBins();
	cannedmaxKnockRetardTable();
	cannedlambdaRpmBins();
	cannedlambdaLoadBins();
	cannedlambdaTable();
	cannedgppwm1_rpmBins();
	cannedgppwm1_table();
	cannedinjectorStagingRpmBins();
	cannedinjectorStagingLoadBins();
	cannedinjectorStagingTable();
	cannedhpfpTargetRpmBins();
	cannedhpfpTargetLoadBins();
	cannedhpfpCompensationRpmBins();
	cannedhpfpCompensationLoadBins();
	cannedhpfpCompensation();
```
