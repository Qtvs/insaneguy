[1] = {
	["children"] = {
		[1] = {
			["children"] = {
				[1] = {
					["children"] = {
					},
					["self"] = {
						["Overlapping"] = true,
						["ClassName"] = "sound",
						["UniqueID"] = "3253254660",
						["Sound"] = "freak_fortress_2/team_killer/teamkiller_death.mp3",
					},
				},
			},
			["self"] = {
				["ClassName"] = "event",
				["UniqueID"] = "642669677",
				["Event"] = "health_lost",
				["Operator"] = "equal",
				["Arguments"] = "100",
				["Invert"] = true,
			},
		},
	},
	["self"] = {
		["ClassName"] = "group",
		["UniqueID"] = "2684855068",
		["Name"] = "death",
	},
},
[2] = {
	["children"] = {
		[1] = {
			["children"] = {
				[1] = {
					["children"] = {
					},
					["self"] = {
						["ClassName"] = "sunbeams",
						["Position"] = Vector(0, 0, 49.125),
						["Multiplier"] = -0.45,
						["Darken"] = 0.3,
						["Bone"] = "",
						["Size"] = 82.65,
						["UniqueID"] = "36760780",
					},
				},
				[2] = {
					["children"] = {
					},
					["self"] = {
						["DamageType"] = "alwaysgib",
						["UniqueID"] = "1529616520",
						["Speed"] = 10.4,
						["Physical"] = true,
						["AimDir"] = true,
						["LifeTime"] = 0.1,
						["ClassName"] = "projectile",
						["Bone"] = "",
						["Mass"] = 1000,
						["Damage"] = 1000,
						["Position"] = Vector(0, 0, 49.6533203125),
						["Gravity"] = false,
					},
				},
				[3] = {
					["children"] = {
					},
					["self"] = {
						["Event"] = "timer",
						["Arguments"] = "10@@10",
						["UniqueID"] = "1680037615",
						["ClassName"] = "event",
					},
				},
				[4] = {
					["children"] = {
					},
					["self"] = {
						["Overlapping"] = true,
						["ClassName"] = "sound",
						["UniqueID"] = "1939418120",
						["Sound"] = "freak_fortress_2/team_killer/teamkiller_rage.wav",
					},
				},
				[5] = {
					["children"] = {
					},
					["self"] = {
						["DamageType"] = "alwaysgib",
						["UniqueID"] = "1529616520",
						["Speed"] = 10.4,
						["Physical"] = true,
						["AimDir"] = true,
						["LifeTime"] = 0.1,
						["ClassName"] = "projectile",
						["Bone"] = "",
						["Mass"] = 1000,
						["Angles"] = Angle(-0, 156.14695739746, 0),
						["Damage"] = 1000,
						["Position"] = Vector(0, 0, 49.6533203125),
						["Gravity"] = false,
					},
				},
				[6] = {
					["children"] = {
					},
					["self"] = {
						["DamageType"] = "alwaysgib",
						["UniqueID"] = "2415033947",
						["Speed"] = 10.4,
						["Physical"] = true,
						["AimDir"] = true,
						["LifeTime"] = 0.1,
						["ClassName"] = "projectile",
						["Bone"] = "",
						["Mass"] = 1000,
						["Angles"] = Angle(-0, -114.67217254639, 0),
						["Damage"] = 1000,
						["Position"] = Vector(0, 0, 49.6533203125),
						["Gravity"] = false,
					},
				},
				[7] = {
					["children"] = {
					},
					["self"] = {
						["DamageType"] = "alwaysgib",
						["UniqueID"] = "1529616520",
						["Speed"] = 10.4,
						["Physical"] = true,
						["AimDir"] = true,
						["LifeTime"] = 0.1,
						["ClassName"] = "projectile",
						["Bone"] = "",
						["Mass"] = 1000,
						["Angles"] = Angle(-0, 72.51895904541, 0),
						["Damage"] = 1000,
						["Position"] = Vector(0, 0, 49.6533203125),
						["Gravity"] = false,
					},
				},
				[8] = {
					["children"] = {
					},
					["self"] = {
						["ClassName"] = "shake",
						["Frequency"] = 40,
						["Duration"] = 40,
						["Amplitude"] = 40,
						["UniqueID"] = "127128181",
					},
				},
			},
			["self"] = {
				["ClassName"] = "event",
				["UniqueID"] = "2799727812",
				["Event"] = "button",
				["Arguments"] = "e",
				["Invert"] = true,
			},
		},
	},
	["self"] = {
		["ClassName"] = "group",
		["UniqueID"] = "364303577",
		["Name"] = "rage",
	},
},
[3] = {
	["children"] = {
		[1] = {
			["children"] = {
				[1] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["Model"] = "models/pac/default.mdl",
								["ClassName"] = "model",
								["UniqueID"] = "1010921696",
								["Size"] = 0,
								["EditorExpand"] = true,
								["Bone"] = "",
								["Name"] = "aimpoint offset",
								["Position"] = Vector(38, 0, 0),
							},
						},
					},
					["self"] = {
						["ClassName"] = "model",
						["UniqueID"] = "2554496253",
						["Model"] = "models/pac/default.mdl",
						["Size"] = 0,
						["Bone"] = "hitpos_ent_ang_zero_pitch",
						["Name"] = "aim point",
						["EditorExpand"] = true,
					},
				},
				[2] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["ClassName"] = "model",
								["UniqueID"] = "351823559",
								["Model"] = "models/pac/default.mdl",
								["Size"] = 0,
								["Name"] = "head follow",
								["Angles"] = Angle(0, 90, -90),
							},
						},
					},
					["self"] = {
						["Position"] = Vector(0, -4, 0),
						["AimPartUID"] = "1010921696",
						["Name"] = "head origin",
						["Scale"] = Vector(1.7000000476837, 1, 1),
						["Material"] = "models/weapons/v_crowbar/head_uvw",
						["ClassName"] = "model",
						["Size"] = 0,
						["AimPartName"] = "aimpoint offset",
						["EditorExpand"] = true,
						["Bone"] = "bip neck",
						["Model"] = "models/pac/default.mdl",
						["UniqueID"] = "3330122862",
					},
				},
				[3] = {
					["children"] = {
					},
					["self"] = {
						["FollowAnglesOnly"] = true,
						["ClassName"] = "bone",
						["UniqueID"] = "68316071",
						["FollowPartName"] = "head follow",
						["Bone"] = "bip head",
						["FollowPartUID"] = "351823559",
					},
				},
			},
			["self"] = {
				["Name"] = "head aim",
				["ClassName"] = "group",
				["UniqueID"] = "3248913488",
				["EditorExpand"] = true,
			},
		},
		[2] = {
			["children"] = {
				[1] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["ClassName"] = "proxy",
								["UniqueID"] = "3916476839",
								["Expression"] = "nil, nil, owner_eye_angle_pitch()*-50 + 25",
								["Input"] = "owner_eye_angle_pitch",
								["VariableName"] = "Angles",
							},
						},
					},
					["self"] = {
						["Angles"] = Angle(0, 0, 4.6067366600037),
						["UniqueID"] = "3706039830",
						["Bone"] = "bip spine  0",
						["ClassName"] = "bone",
						["EditorExpand"] = true,
					},
				},
				[2] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["EditorExpand"] = true,
								["UniqueID"] = "2768103191",
								["Expression"] = "nil, nil, owner_eye_angle_pitch()*-50 + 25",
								["ClassName"] = "proxy",
								["Input"] = "owner_eye_angle_pitch",
								["VariableName"] = "Angles",
							},
						},
					},
					["self"] = {
						["Angles"] = Angle(0, 0, 4.6067366600037),
						["UniqueID"] = "3883955167",
						["Bone"] = "bip spine  1",
						["ClassName"] = "bone",
						["EditorExpand"] = true,
					},
				},
			},
			["self"] = {
				["Name"] = "body pitch",
				["ClassName"] = "group",
				["UniqueID"] = "3391528412",
				["EditorExpand"] = true,
			},
		},
		[3] = {
			["children"] = {
			},
			["self"] = {
				["EditorExpand"] = true,
				["UniqueID"] = "3794698230",
				["Bone"] = "none",
				["Model"] = "models/freak_fortress_2/teamkiller/teamkiller_v4.mdl",
				["ClassName"] = "entity",
			},
		},
		[4] = {
			["children"] = {
				[1] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["Fallback"] = "run_MELEE",
								["UniqueID"] = "1142180148",
								["ReloadCrouch"] = "ReloadCrouch_LOSER",
								["ActLand"] = "jumpLand_melee",
								["CrouchWalk"] = "Crouch_Walk_MELEE",
								["SwimIdle"] = "Swim_LOSER",
								["Noclip"] = "Airwalk_MELEE",
								["Run"] = "run_MELEE",
								["ClassName"] = "holdtype",
								["Air"] = "Jump_Float_melee",
								["EditorExpand"] = true,
								["CrouchIdle"] = "Crouch_MELEE",
								["Swim"] = "Swim_MELEE",
								["StandIdle"] = "Stand_MELEE",
								["Jump"] = "Jump_Start_melee",
							},
						},
						[2] = {
							["children"] = {
							},
							["self"] = {
								["Arguments"] = "normal",
								["Invert"] = true,
								["UniqueID"] = "44235598",
								["Event"] = "holdtype",
								["Operator"] = "equal",
								["EditorExpand"] = true,
								["ClassName"] = "event",
							},
						},
					},
					["self"] = {
						["Position"] = Vector(1.79345703125, 2.2670288085938, -3.9368896484375),
						["Angles"] = Angle(-90, 0, -90),
						["UniqueID"] = "1299149497",
						["EditorExpand"] = true,
						["ClassName"] = "entity",
						["Bone"] = "weapon_bone_ 2",
						["Name"] = "hander",
						["Weapon"] = true,
					},
				},
				[2] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["Arguments"] = "physgun;smg;shotgun;crossbow;rpg",
								["Invert"] = true,
								["UniqueID"] = "4046565299",
								["Event"] = "holdtype",
								["Operator"] = "equal",
								["EditorExpand"] = true,
								["ClassName"] = "event",
							},
						},
						[2] = {
							["children"] = {
							},
							["self"] = {
								["UniqueID"] = "1633433427",
								["Jump"] = "Jump_Start_primary",
								["AttackStandPrimaryfire"] = "AttackStand_PRIMARY",
								["Run"] = "Run_PRIMARY",
								["CrouchIdle"] = "Crouch_PRIMARY",
								["StandIdle"] = "Stand_PRIMARY",
								["Fallback"] = "Run_PRIMARY",
								["ActRangeAttack1"] = "AttackStand_PRIMARY",
								["Noclip"] = "Airwalk_PRIMARY",
								["SwimIdle"] = "Swim_PRIMARY",
								["ReloadStand"] = "ReloadStand_PRIMARY",
								["AttackCrouchPrimaryfire"] = "AttackCrouch_PRIMARY",
								["EditorExpand"] = true,
								["ReloadCrouch"] = "ReloadCrouch_PRIMARY",
								["ActLand"] = "jumpLand_PRIMARY",
								["CrouchWalk"] = "Crouch_Walk_PRIMARY",
								["Swim"] = "Swim_PRIMARY",
								["Air"] = "Jump_Float_PRIMARY",
								["ClassName"] = "holdtype",
							},
						},
					},
					["self"] = {
						["Position"] = Vector(1.79345703125, 2.2670288085938, -3.9368896484375),
						["Angles"] = Angle(-90, 0, -90),
						["UniqueID"] = "1885440714",
						["EditorExpand"] = true,
						["ClassName"] = "entity",
						["Bone"] = "weapon_bone_ 2",
						["Name"] = "primary",
						["Weapon"] = true,
					},
				},
				[3] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["Arguments"] = "melee;melee2;grenade;slam",
								["Invert"] = true,
								["UniqueID"] = "4167178939",
								["Event"] = "holdtype",
								["Operator"] = "equal",
								["EditorExpand"] = true,
								["ClassName"] = "event",
							},
						},
						[2] = {
							["children"] = {
							},
							["self"] = {
								["Fallback"] = "Run_MELEE",
								["UniqueID"] = "126820848",
								["CrouchWalk"] = "Crouch_Walk_MELEE",
								["Jump"] = "Jump_Start_melee",
								["AttackStandPrimaryfire"] = "MELEE_swing",
								["Noclip"] = "Airwalk_MELEE",
								["EditorExpand"] = true,
								["Run"] = "run_MELEE",
								["ClassName"] = "holdtype",
								["Air"] = "Jump_Float_melee",
								["Swim"] = "Swim_MELEE",
								["CrouchIdle"] = "Crouch_MELEE",
								["ActLand"] = "jumpLand_melee",
								["StandIdle"] = "Stand_MELEE",
								["AttackCrouchPrimaryfire"] = "MELEE_crouch_swing",
							},
						},
					},
					["self"] = {
						["Position"] = Vector(0, 6, -2),
						["Angles"] = Angle(0, -90, -90),
						["UniqueID"] = "1454655852",
						["EditorExpand"] = true,
						["ClassName"] = "entity",
						["Bone"] = "weapon_bone_ 2",
						["Name"] = "melee",
						["Weapon"] = true,
					},
				},
				[4] = {
					["children"] = {
						[1] = {
							["children"] = {
							},
							["self"] = {
								["Arguments"] = "pistol",
								["Invert"] = true,
								["UniqueID"] = "478977194",
								["Event"] = "holdtype",
								["Operator"] = "equal",
								["EditorExpand"] = true,
								["ClassName"] = "event",
							},
						},
						[2] = {
							["children"] = {
							},
							["self"] = {
								["UniqueID"] = "4021620632",
								["Jump"] = "Jump_Start_SECONDARY",
								["AttackStandPrimaryfire"] = "AttackStand_SECONDARY",
								["Run"] = "Run_SECONDARY",
								["CrouchIdle"] = "Crouch_SECONDARY",
								["StandIdle"] = "Stand_SECONDARY",
								["Fallback"] = "Run_SECONDARY",
								["ReloadStand"] = "ReloadStand_SECONDARY",
								["Noclip"] = "Airwalk_SECONDARY",
								["SwimIdle"] = "Swim_SECONDARY",
								["AttackCrouchPrimaryfire"] = "SECONDARY_crouch_swing",
								["EditorExpand"] = true,
								["ReloadCrouch"] = "ReloadCrouch_SECONDARY",
								["ActLand"] = "jumpLand_SECONDARY",
								["CrouchWalk"] = "Crouch_Walk_SECONDARY",
								["Swim"] = "Swim_SECONDARY",
								["Air"] = "Jump_Float_SECONDARY",
								["ClassName"] = "holdtype",
							},
						},
					},
					["self"] = {
						["Position"] = Vector(-0.40000000596046, 4, 0.5),
						["Angles"] = Angle(90, 180, 90),
						["UniqueID"] = "4107862047",
						["EditorExpand"] = true,
						["ClassName"] = "entity",
						["Bone"] = "weapon_bone_ 2",
						["Name"] = "secondary",
						["Weapon"] = true,
					},
				},
			},
			["self"] = {
				["Name"] = "holdtypes",
				["ClassName"] = "group",
				["UniqueID"] = "2404083068",
				["EditorExpand"] = true,
			},
		},
	},
	["self"] = {
		["ClassName"] = "group",
		["UniqueID"] = "1008348447",
		["Name"] = "team killer",
	},
},
[4] = {
	["children"] = {
		[1] = {
			["children"] = {
				[1] = {
					["children"] = {
					},
					["self"] = {
						["Overlapping"] = true,
						["ClassName"] = "sound",
						["UniqueID"] = "1880817003",
						["Sound"] = "freak_fortress_2/team_killer/teamkiller_bgm.mp3",
					},
				},
				[2] = {
					["children"] = {
					},
					["self"] = {
						["Overlapping"] = true,
						["ClassName"] = "sound",
						["UniqueID"] = "56251480",
						["Sound"] = "freak_fortress_2/team_killer/teamkiller_intro2.mp3",
					},
				},
			},
			["self"] = {
				["ClassName"] = "event",
				["UniqueID"] = "4089057455",
				["Event"] = "say",
				["Operator"] = "equal",
				["Arguments"] = "killer@@272",
				["Invert"] = true,
			},
		},
	},
	["self"] = {
		["ClassName"] = "group",
		["UniqueID"] = "1051014216",
		["Name"] = "spawn",
	},
},
[5] = {
	["children"] = {
		[1] = {
			["children"] = {
				[1] = {
					["children"] = {
					},
					["self"] = {
						["ClassName"] = "event",
						["UniqueID"] = "552334571",
						["Event"] = "weapon_class",
						["Operator"] = "equal",
						["Arguments"] = "weapon_crowbar@@1",
						["Invert"] = true,
					},
				},
			},
			["self"] = {
				["Alpha"] = 0,
				["ClassName"] = "model",
				["UniqueID"] = "477954265",
				["Model"] = "models/pac/default.mdl",
			},
		},
	},
	["self"] = {
		["Name"] = "my outfit",
		["ClassName"] = "group",
		["UniqueID"] = "612194415",
		["Description"] = "add parts to me!",
	},
},
[6] = {
	["children"] = {
		[1] = {
			["children"] = {
				[1] = {
					["children"] = {
					},
					["self"] = {
						["DamageType"] = "alwaysgib",
						["UniqueID"] = "545363901",
						["Speed"] = 2.4,
						["Physical"] = true,
						["LifeTime"] = 0.2,
						["ClassName"] = "projectile",
						["Bone"] = "",
						["Position"] = Vector(0.00152587890625, 0.0018310546875, 46.85546875),
						["Damage"] = 140.8,
						["EyeAngles"] = true,
						["Gravity"] = false,
					},
				},
				[2] = {
					["children"] = {
					},
					["self"] = {
						["ClassName"] = "event",
						["UniqueID"] = "2584709190",
						["Event"] = "weapon_class",
						["Operator"] = "equal",
						["Arguments"] = "weapon_crowbar@@1",
						["Invert"] = true,
					},
				},
				[3] = {
					["children"] = {
					},
					["self"] = {
						["Overlapping"] = true,
						["ClassName"] = "sound",
						["UniqueID"] = "3079350395",
						["Sound"] = "freak_fortress_2/team_killer/teamkiller_hit.mp3;freak_fortress_2/team_killer/teamkiller_hit2.mp3;freak_fortress_2/team_killer/teamkiller_hit3.mp3;freak_fortress_2/team_killer/teamkiller_hit4.mp3",
					},
				},
			},
			["self"] = {
				["ClassName"] = "event",
				["UniqueID"] = "1613906651",
				["Event"] = "animation_event",
				["Arguments"] = "attack@@0.1",
				["Invert"] = true,
			},
		},
	},
	["self"] = {
		["ClassName"] = "group",
		["UniqueID"] = "1947366140",
		["Name"] = "melee hit",
	},
},
