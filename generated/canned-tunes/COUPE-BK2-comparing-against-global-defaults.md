# COUPE-BK2-comparing-against-global-defaults

// canned tune https://rusefi.com/online/view.php?msq=1507

```
    // default "Single Coil"
    engineConfiguration->ignitionMode = IM_INDIVIDUAL_COILS;
    // default 1.65
    engineConfiguration->displacement = 1.998;
    // default "false"
    engineConfiguration->isForcedInduction = true;
    // default 0.0
    engineConfiguration->globalTriggerAngleOffset = 475;
    // default 450.0
    engineConfiguration->vvtOffsets[0] = -154;
    // default 0.0
    engineConfiguration->vvtOffsets[1] = 335;
    // default 200.0
    engineConfiguration->injector.flow = 629.03;
    // default "None"
    engineConfiguration->injectorCompensationMode = ICM_FixedRailPressure;
    // default 300.0
    engineConfiguration->fuelReferencePressure = 586.0544;
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
    // default "Aux Linear 1"
    engineConfiguration->veBlends[2].blendParameter = GPPWM_Zero;
    // default "IAT"
    engineConfiguration->boostOpenLoopBlends[0].blendParameter = GPPWM_Zero;
    // default "Aux Temp 2"
    engineConfiguration->boostClosedLoopBlends[1].blendParameter = GPPWM_Zero;
    // default 0.0
    engineConfiguration->tpsMin = 98;
    // default 1000.0
    engineConfiguration->tpsMax = 926;
    // default 1000.0
    engineConfiguration->tps1SecondaryMin = 891;
    // default 0.0
    engineConfiguration->tps1SecondaryMax = 69;
    // default 0.0
    engineConfiguration->throttlePedalUpVoltage = 0.73;
    // default 5.0
    engineConfiguration->throttlePedalWOTVoltage = 4;
    // default 5.0
    engineConfiguration->throttlePedalSecondaryUpVoltage = 0.34;
    // default 0.0
    engineConfiguration->throttlePedalSecondaryWOTVoltage = 1.86;
    // default "Normal"
    engineConfiguration->clutchDownPinInverted = false;
    // default "Normal"
    engineConfiguration->clutchUpPinInverted = false;
    // default 300.0
    engineConfiguration->idle.solenoidFrequency = 200;
    // default "false"
    engineConfiguration->stepperDcInvertedPins = true;
    // default "false"
    engineConfiguration->useSeparateAdvanceForIdle = true;
    // default 0.0
    engineConfiguration->iacByTpsHoldTime = 2;
    // default 0.0
    engineConfiguration->iacByTpsDecayTime = 3;
    // default "false"
    engineConfiguration->useIdleTimingPidControl = true;
    // default 0.0
    engineConfiguration->idleTimingPid.dFactor = 5.0E-5;
    // default 92.0
    engineConfiguration->fanOnTemperature = 80;
    // default 88.0
    engineConfiguration->fanOffTemperature = 75;
    // default "false"
    engineConfiguration->disableFan1WhenStopped = true;
    // default 95.0
    engineConfiguration->fan2OnTemperature = 87;
    // default 91.0
    engineConfiguration->fan2OffTemperature = 82;
    // default "false"
    engineConfiguration->disableFan2WhenStopped = true;
    // default "false"
    engineConfiguration->enableSoftwareKnock = true;
    // default 20.0
    engineConfiguration->knockRetardAggression = 0;
    // default 3.0
    engineConfiguration->knockRetardReapplyRate = 0;
    // default 550.0
    engineConfiguration->vvtControlMinRpm = 1500;
    // default "advance"
    engineConfiguration->invertVvtControlExhaust = retard;
    // default 33.0
    engineConfiguration->auxPid[0].offset = 38;
    // default 0.005
    engineConfiguration->auxPid[0].iFactor = 25.4;
    // default 0.0
    engineConfiguration->auxPid[0].dFactor = 0.1;
    // default 0.0
    engineConfiguration->auxPid[1].offset = 38;
    // default 0.0
    engineConfiguration->auxPid[1].pFactor = 2;
    // default 0.0
    engineConfiguration->auxPid[1].iFactor = 25.4;
    // default 0.0
    engineConfiguration->auxPid[1].dFactor = 0.2;
    // default "MAP"
    engineConfiguration->debugMode = DBG_22;
    // default 200.0
    engineConfiguration->rpmSoftLimitWindowSize = 0;
    // default 4.0
    engineConfiguration->rpmSoftLimitTimingRetard = 0;
    // default 250.0
    engineConfiguration->etbRevLimitRange = 0;
    // default 50.0
    engineConfiguration->crankingIACposition = 70;
    // default 200.0
    engineConfiguration->afterCrankingIACtaperDuration = 100;
    // default "false"
    engineConfiguration->overrideCrankingIacSetting = true;
    // default 0.0
    engineConfiguration->tpsAccelLookback = 0.3;
    // default 40.0
    engineConfiguration->tpsAccelEnrichmentThreshold = 12;
    // default 0.0
    engineConfiguration->tpsDecelEnleanmentThreshold = 7;
    // default 0.0
    engineConfiguration->tpsAccelFractionPeriod = 3;
    // default 1.0
    engineConfiguration->tpsAccelFractionDivisor = 3;
    // default 2000.0
    engineConfiguration->boostControlMinRpm = 0;
    // default 30.0
    engineConfiguration->boostControlMinTps = 0;
    // default 110.0
    engineConfiguration->boostControlMinMap = 0;
    // default "Throttle 2"
    engineConfiguration->etbFunctions[1] = DC_Wastegate;
    // default 1.0
    engineConfiguration->etb.pFactor = 8.8944;
    // default 10.0
    engineConfiguration->etb.iFactor = 70.2307;
    // default 0.05
    engineConfiguration->etb.dFactor = 0.1855;


	coupleBK2cannedknockNoiseRpmBins();
	coupleBK2cannedknockBaseNoise();
	coupleBK2canneddwellVoltageCorrVoltBins();
	coupleBK2canneddwellVoltageCorrValues();
	coupleBK2cannedtpsTspCorrValuesBins();
	coupleBK2cannedtpsTspCorrValues();
	coupleBK2cannedprimeBins();
	coupleBK2cannedprimeValues();
	coupleBK2cannedmap_samplingAngleBins();
	coupleBK2cannedmap_samplingWindowBins();
	coupleBK2cannedvrThreshold1_rpmBins();
	coupleBK2cannedvrThreshold2_rpmBins();
	coupleBK2cannedmafDecodingBins();
	coupleBK2cannedmafDecoding();
	coupleBK2cannediatFuelCorrBins();
	coupleBK2cannediatFuelCorr();
	coupleBK2cannedcltFuelCorrBins();
	coupleBK2cannedcltFuelCorr();
	coupleBK2cannedcrankingFuelBins();
	coupleBK2cannedcrankingFuelCoef();
	coupleBK2cannedcrankingFuelCoefE100();
	coupleBK2cannedcltRevLimitRpmBins();
	coupleBK2cannedcltRevLimitRpm();
	coupleBK2cannedcrankingCycleBins();
	coupleBK2cannedcrankingCycleCoef();
	coupleBK2cannedcltIdleCorrBins();
	coupleBK2cannedcltIdleCorr();
	coupleBK2cannedcltCrankingCorr();
	coupleBK2cannedcltIdleRpm();
	coupleBK2cannedidleAdvanceBins();
	coupleBK2cannedidleAdvance();
	coupleBK2cannedfuelLevelBins();
	coupleBK2cannedfuelLevelValues();
	coupleBK2cannedhpfpLobeProfileQuantityBins();
	coupleBK2cannedhpfpLobeProfileAngle();
	coupleBK2cannedhpfpDeadtimeVoltsBins();
	coupleBK2cannedwwCltBins();
	coupleBK2cannedwwTauCltValues();
	coupleBK2cannedwwMapBins();
	coupleBK2cannedwwTauMapValues();
	coupleBK2cannedwwBetaCltValues();
	coupleBK2cannedwwBetaMapValues();
	coupleBK2cannedtcu_tccTpsBins();
	coupleBK2cannedtcu_tccLockSpeed();
	coupleBK2cannedtcu_tccUnlockSpeed();
	coupleBK2cannedtcu_pcAirmassBins();
	coupleBK2cannedtcu_pcValsR();
	coupleBK2cannedtcu_pcValsN();
	coupleBK2cannedtcu_pcVals1();
	coupleBK2cannedtcu_pcVals2();
	coupleBK2cannedtcu_pcVals3();
	coupleBK2cannedtcu_pcVals4();
	coupleBK2cannedtcu_pcVals12();
	coupleBK2cannedtcu_pcVals23();
	coupleBK2cannedtcu_pcVals34();
	coupleBK2cannedtcu_pcVals21();
	coupleBK2cannedtcu_pcVals32();
	coupleBK2cannedtcu_pcVals43();
	coupleBK2cannedtcu_32SpeedBins();
	coupleBK2cannedtcu_32Vals();
	coupleBK2cannedtcu_rangeM();
	coupleBK2cannedtcu_rangeM3();
	coupleBK2cannedtcu_rangeM2();
	coupleBK2cannedtcu_rangeM1();
	coupleBK2cannedignBlends1_blendBins();
	coupleBK2cannedignBlends2_blendBins();
	coupleBK2cannedignBlends2_blendValues();
	coupleBK2cannedveBlends3_blendBins();
	coupleBK2cannedveBlends4_blendBins();
	coupleBK2cannedveBlends4_blendValues();
	coupleBK2cannedboostOpenLoopBlends1_blendBins();
	coupleBK2cannedboostClosedLoopBlends2_blendBins();
	coupleBK2cannedthrottleEstimateEffectiveAreaBins();
	coupleBK2cannedtpsTpsAccelFromRpmBins();
	coupleBK2cannedtpsTpsAccelToRpmBins();
	coupleBK2cannedtpsTpsAccelTable();
	coupleBK2cannedboostRpmBins();
	coupleBK2cannedboostTableOpenLoop();
	coupleBK2cannedvvtTable1RpmBins();
	coupleBK2cannedvvtTable1LoadBins();
	coupleBK2cannedvvtTable1();
	coupleBK2cannedvvtTable2RpmBins();
	coupleBK2cannedvvtTable2LoadBins();
	coupleBK2cannedvvtTable2();
	coupleBK2cannedscriptTable1RpmBins();
	coupleBK2cannedscriptTable1LoadBins();
	coupleBK2cannedscriptTable2RpmBins();
	coupleBK2cannedscriptTable2LoadBins();
	coupleBK2cannedscriptTable3RpmBins();
	coupleBK2cannedscriptTable3LoadBins();
	coupleBK2cannedscriptTable3();
	coupleBK2cannedscriptTable4RpmBins();
	coupleBK2cannedscriptTable4LoadBins();
	coupleBK2cannedscriptTable4();
	coupleBK2cannedalsIgnRetardrpmBins();
	coupleBK2cannedalsIgnRetardLoadBins();
	coupleBK2cannedALSTimingRetardTable();
	coupleBK2cannedalsFuelAdjustmentrpmBins();
	coupleBK2cannedalsFuelAdjustmentLoadBins();
	coupleBK2cannedALSFuelAdjustment();
	coupleBK2cannedalsIgnSkiprpmBins();
	coupleBK2cannedalsIgnSkipLoadBins();
	coupleBK2cannedALSIgnSkipTable();
	coupleBK2cannedignitionRpmBins();
	coupleBK2cannedignitionLoadBins();
	coupleBK2cannedignitionTable();
	coupleBK2cannedignBlends1_rpmBins();
	coupleBK2cannedignBlends1_loadBins();
	coupleBK2cannedignBlends1_table();
	coupleBK2cannedignBlends2_rpmBins();
	coupleBK2cannedignBlends2_loadBins();
	coupleBK2cannedignBlends2_table();
	coupleBK2cannedignBlends3_table();
	coupleBK2cannedveBlends1_table();
	coupleBK2cannedveBlends2_loadBins();
	coupleBK2cannedveBlends2_table();
	coupleBK2cannedveBlends3_rpmBins();
	coupleBK2cannedveBlends3_loadBins();
	coupleBK2cannedveBlends3_table();
	coupleBK2cannedboostOpenLoopBlends1_rpmBins();
	coupleBK2cannedboostClosedLoopBlends1_table();
	coupleBK2cannedboostClosedLoopBlends2_rpmBins();
	coupleBK2cannedboostClosedLoopBlends2_loadBins();
	coupleBK2cannedboostClosedLoopBlends2_table();
	coupleBK2cannedignitionIatCorrTempBins();
	coupleBK2cannedignitionIatCorrLoadBins();
	coupleBK2cannedignitionIatCorrTable();
	coupleBK2cannedveRpmBins();
	coupleBK2cannedveLoadBins();
	coupleBK2cannedveTable();
	coupleBK2cannedfuelTrimRpmBins();
	coupleBK2cannedfuelTrimLoadBins();
	coupleBK2cannedfuelTrims1_table();
	coupleBK2cannedfuelTrims2_table();
	coupleBK2cannedfuelTrims3_table();
	coupleBK2cannedfuelTrims4_table();
	coupleBK2cannedfuelTrims5_table();
	coupleBK2cannedfuelTrims6_table();
	coupleBK2cannedfuelTrims7_table();
	coupleBK2cannedfuelTrims8_table();
	coupleBK2cannedfuelTrims9_table();
	coupleBK2cannedfuelTrims10_table();
	coupleBK2cannedfuelTrims11_table();
	coupleBK2cannedfuelTrims12_table();
	coupleBK2cannedignTrimRpmBins();
	coupleBK2cannedignTrimLoadBins();
	coupleBK2cannedignTrims1_table();
	coupleBK2cannedignTrims2_table();
	coupleBK2cannedignTrims3_table();
	coupleBK2cannedignTrims4_table();
	coupleBK2cannedignTrims5_table();
	coupleBK2cannedignTrims6_table();
	coupleBK2cannedignTrims7_table();
	coupleBK2cannedignTrims8_table();
	coupleBK2cannedignTrims9_table();
	coupleBK2cannedignTrims10_table();
	coupleBK2cannedignTrims11_table();
	coupleBK2cannedignTrims12_table();
	coupleBK2cannedmapEstimateRpmBins();
	coupleBK2cannedmapEstimateTpsBins();
	coupleBK2cannedmapEstimateTable();
	coupleBK2cannedinjPhaseRpmBins();
	coupleBK2cannedinjPhaseLoadBins();
	coupleBK2cannedinjectionPhase();
	coupleBK2cannedpedalToTpsRpmBins();
	coupleBK2cannedpedalToTpsTable();
	coupleBK2cannedthrottle2TrimRpmBins();
	coupleBK2cannedthrottle2TrimTpsBins();
	coupleBK2cannedthrottle2TrimTable();
	coupleBK2cannedmaxKnockRetardRpmBins();
	coupleBK2cannedmaxKnockRetardLoadBins();
	coupleBK2cannedmaxKnockRetardTable();
	coupleBK2cannedlambdaRpmBins();
	coupleBK2cannedlambdaLoadBins();
	coupleBK2cannedlambdaTable();
	coupleBK2cannedhpfpTargetRpmBins();
	coupleBK2cannedhpfpTargetLoadBins();
	coupleBK2cannedhpfpCompensationRpmBins();
	coupleBK2cannedhpfpCompensationLoadBins();
	coupleBK2cannedhpfpCompensation();
	coupleBK2cannedpostCrankingFactor();
```
