# Copyright (C) 2019 by Sukchan Lee <acetcom@gmail.com>

# This file is part of Open5GS.

# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU Affero General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <https://www.gnu.org/licenses/>.

libsbi_openapi_sources = files('''
    src/list.c
    src/apiKey.c
    src/binary.c
    external/cJSON.c
    model/object.c
    model/access_type.c
    model/amf_cond.c
    model/amf_info.c
    model/atsss_capability.c
    model/ausf_info.c
    model/bsf_info.c
    model/change_item.c
    model/change_type.c
    model/chf_info.c
    model/chf_service_info.c
    model/data_set_id.c
    model/default_notification_subscription.c
    model/dnn_smf_info_item.c
    model/dnn_upf_info_item.c
    model/event_id.c
    model/guami.c
    model/guami_list_cond.c
    model/identity_range.c
    model/inline_response_200.c
    model/interface_upf_info_item.c
    model/invalid_param.c
    model/ip_end_point.c
    model/ipv4_address_range.c
    model/ipv6_prefix_range.c
    model/link.c
    model/links_value_schema.c
    model/n1_message_class.c
    model/n2_information_class.c
    model/n2_interface_amf_info.c
    model/network_slice_cond.c
    model/nf_group_cond.c
    model/nf_instance_id_cond.c
    model/nf_profile.c
    model/nf_service.c
    model/nf_service_status.c
    model/nf_service_version.c
    model/nf_status.c
    model/nf_type.c
    model/nf_type_cond.c
    model/notif_condition.c
    model/notification_data.c
    model/notification_event_type.c
    model/notification_type.c
    model/nrf_info.c
    model/nwdaf_event.c
    model/nwdaf_info.c
    model/patch_item.c
    model/patch_operation.c
    model/pcf_info.c
    model/pdu_session_type.c
    model/plmn_id.c
    model/plmn_range.c
    model/plmn_snssai.c
    model/problem_details.c
    model/service_name_cond.c
    model/smf_info.c
    model/snssai.c
    model/snssai_smf_info_item.c
    model/snssai_upf_info_item.c
    model/subscription_data.c
    model/supi_range.c
    model/tac_range.c
    model/tai.c
    model/tai_range.c
    model/transport_protocol.c
    model/udm_info.c
    model/udr_info.c
    model/up_interface_type.c
    model/upf_info.c
    model/uri_scheme.c

    model/atom.c
    model/cnf.c
    model/cnf_unit.c
    model/complex_query.c
    model/dnf.c
    model/dnf_unit.c
    model/search_result.c
    model/stored_search_result.c

    model/af_event.c
    model/af_event_exposure_data.c
    model/an_node_type.c
    model/external_client_type.c
    model/gmlc_info.c
    model/hss_info.c
    model/imsi_range.c
    model/internal_group_id_range.c
    model/lmf_info.c
    model/nef_info.c
    model/nf_info.c
    model/nf_service_set_cond.c
    model/nf_set_cond.c
    model/pcscf_info.c
    model/pfd_data.c
    model/plmn_id_nid.c
    model/preferred_search.c
    model/rat_type.c
    model/tngf_info.c
    model/twif_info.c
    model/udsf_info.c
    model/upf_cond.c
    model/vendor_specific_feature.c
    model/w_agf_info.c

    model/auth_result.c
    model/auth_type.c
    model/authentication_info.c
    model/av5g_aka.c
    model/confirmation_data.c
    model/confirmation_data_response.c
    model/eap_session.c
    model/resynchronization_info.c
    model/rg_auth_ctx.c
    model/rg_authentication_info.c
    model/trace_data.c
    model/trace_depth.c
    model/ue_authentication_ctx.c

    model/auth_event.c
    model/authentication_info_request.c
    model/authentication_info_result.c
    model/authentication_vector.c
    model/av5_g_he_aka.c
    model/av_eap_aka_prime.c
    model/av_eps_aka.c
    model/av_ims_gba_eap_aka.c
    model/av_type.c
    model/hss_auth_type.c
    model/hss_authentication_info_request.c
    model/hss_authentication_info_result.c
    model/hss_authentication_vectors.c
    model/hss_av_type.c

    model/amf3_gpp_access_registration.c
    model/amf3_gpp_access_registration_modification.c
    model/amf_dereg_info.c
    model/amf_non3_gpp_access_registration.c
    model/amf_non3_gpp_access_registration_modification.c
    model/backup_amf_info.c
    model/cm_info.c
    model/cm_info_report.c
    model/cm_state.c
    model/deregistration_data.c
    model/deregistration_reason.c
    model/eps_interworking_info.c
    model/eps_iwk_pgw.c
    model/ims_vo_ps.c
    model/location_info.c
    model/network_node_diameter_address.c
    model/patch_result.c
    model/pcscf_restoration_notification.c
    model/pei_update_info.c
    model/registration_reason.c
    model/report_item.c
    model/smf_registration.c
    model/smf_registration_info.c
    model/smsf_registration.c
    model/trigger_request.c
    model/vgmlc_address.c

    model/access_and_mobility_subscription_data.c
    model/access_tech.c
    model/acknowledge_info.c
    model/acs_info.c
    model/additional_snssai_data.c
    model/af_external.c
    model/af_non_external.c
    model/ambr.c
    model/ambr_rm.c
    model/app_descriptor.c
    model/app_port_id.c
    model/area.c
    model/arp.c
    model/battery_indication.c
    model/cag_data.c
    model/cag_info.c
    model/civic_address.c
    model/code_word_ind.c
    model/core_network_type.c
    model/data_set_name.c
    model/dnn_configuration.c
    model/dnn_info.c
    model/ec_restriction_data.c
    model/ecgi.c
    model/edrx_parameters.c
    model/ellipsoid_arc.c
    model/ellipsoid_arc_all_of.c
    model/emergency_info.c
    model/enhanced_coverage_restriction_data.c
    model/expected_ue_behaviour_data.c
    model/external_unrelated_class.c
    model/frame_route_info.c
    model/g_nb_id.c
    model/gad_shape.c
    model/geographic_area.c
    model/geographical_coordinates.c
    model/global_ran_node_id.c
    model/group_identifiers.c
    model/id_translation_result.c
    model/ip_address.c
    model/lcs_client_class.c
    model/lcs_client_external.c
    model/lcs_client_group_external.c
    model/lcs_client_non_external.c
    model/lcs_mo_data.c
    model/lcs_mo_service_class.c
    model/lcs_privacy_data.c
    model/location_area.c
    model/location_privacy_ind.c
    model/lpi.c
    model/lte_v2x_auth.c
    model/maximum_latency.c
    model/maximum_response_time.c
    model/modification_notification.c
    model/ncgi.c
    model/network_area_info.c
    model/nidd_information.c
    model/non_external_unrelated_class.c
    model/notify_item.c
    model/nr_v2x_auth.c
    model/nssai.c
    model/null_value.c
    model/odb_packet_services.c
    model/operation_mode.c
    model/pdu_session.c
    model/pdu_session_continuity_ind.c
    model/pdu_session_types.c
    model/pgw_info.c
    model/plmn_ec_info.c
    model/plmn_operator_class.c
    model/point.c
    model/point_all_of.c
    model/point_altitude.c
    model/point_altitude_all_of.c
    model/point_altitude_uncertainty.c
    model/point_altitude_uncertainty_all_of.c
    model/point_uncertainty_circle.c
    model/point_uncertainty_circle_all_of.c
    model/point_uncertainty_ellipse.c
    model/point_uncertainty_ellipse_all_of.c
    model/polygon.c
    model/polygon_all_of.c
    model/preemption_capability.c
    model/preemption_vulnerability.c
    model/privacy_check_related_action.c
    model/ptw_parameters.c
    model/restriction_type.c
    model/scheduled_communication_time.c
    model/scheduled_communication_type.c
    model/sdm_subs_modification.c
    model/sdm_subscription.c
    model/service_area_restriction.c
    model/service_type_unrelated_class.c
    model/session_management_subscription_data.c
    model/shared_data.c
    model/smf_selection_subscription_data.c
    model/sms_management_subscription_data.c
    model/sms_subscription_data.c
    model/smsf_info.c
    model/snssai_info.c
    model/sor_info.c
    model/sor_update_indicator.c
    model/sor_update_info.c
    model/ssc_mode.c
    model/ssc_modes.c
    model/stationary_indication.c
    model/steering_container.c
    model/steering_info.c
    model/subscribed_default_qos.c
    model/subscription_data_sets.c
    model/suggested_packet_num_dl.c
    model/supported_gad_shapes.c
    model/tmbr.c
    model/trace_data_response.c
    model/traffic_profile.c
    model/ue_auth.c
    model/ue_context_in_smf_data.c
    model/ue_context_in_smsf_data.c
    model/ue_id.c
    model/uncertainty_ellipse.c
    model/unrelated_class.c
    model/up_confidentiality.c
    model/up_integrity.c
    model/up_security.c
    model/upu_data.c
    model/upu_info.c
    model/valid_time_period.c
    model/vn_group_data.c

    model/access_and_mobility_data.c
	model/acs_info_rm.c
	model/amf_subscription_info.c
	model/association_type.c
	model/auth_method.c
	model/authentication_subscription.c
	model/authorization_data.c
	model/battery_indication_rm.c
	model/cag_ack_data.c
	model/communication_characteristics.c
	model/data_change_notify.c
	model/datalink_reporting_configuration.c
	model/ddd_traffic_descriptor.c
	model/dl_data_delivery_status.c
	model/domain_name_protocol.c
	model/ec_restriction.c
	model/ee_profile_data.c
	model/ee_subscription.c
	model/eutra_location.c
	model/event_report_mode.c
	model/event_type.c
	model/expected_ue_behaviour.c
	model/exposure_data_change_notification.c
	model/exposure_data_subscription.c
	model/hfc_node_id.c
	model/identity_data.c
	model/lcs_privacy.c
	model/location_accuracy.c
	model/location_reporting_configuration.c
	model/model_5_g_vn_group_configuration.c
	model/model_5_g_vn_group_data.c
	model/monitoring_configuration.c
	model/n3ga_location.c
	model/nr_location.c
	model/nssai_ack_data.c
	model/odb_data.c
	model/operator_specific_data_container.c
	model/pdu_session_management_data.c
	model/pdu_session_status.c
	model/pfd_content.c
	model/pfd_data_for_app.c
	model/pfd_data_for_app_ext.c
	model/pfd_data_for_app_ext_all_of.c
	model/pp_active_time.c
	model/pp_data.c
	model/pp_dl_packet_count_ext.c
	model/pp_maximum_latency.c
	model/pp_maximum_response_time.c
	model/pp_subs_reg_timer.c
	model/problem_details_2.c
	model/provisioned_data_sets.c
	model/reporting_options.c
	model/rm_info.c
	model/rm_state.c
	model/roaming_odb.c
	model/route_information.c
	model/route_to_location.c
	model/scheduled_communication_time_rm.c
	model/scheduled_communication_type_rm.c
	model/sequence_number.c
	model/sign.c
	model/sms_support.c
	model/sor_data.c
	model/sqn_scheme.c
	model/stationary_indication_rm.c
	model/subscription_data_subscriptions.c
	model/traffic_profile_rm.c
	model/ue_reachability.c
	model/ue_update_status.c
	model/upu_data_2.c
	model/user_identifier.c
	model/user_location.c

    model/access_right_status.c
    model/am_policy_data.c
    model/application_data_change_notif.c
    model/application_data_subs.c
    model/bdt_data.c
    model/bdt_policy_data.c
    model/bdt_policy_data_patch.c
    model/charging_information.c
    model/configuration_parameters_eutra.c
    model/configuration_parameters_nr.c
    model/context_data_set_name.c
    model/context_data_sets.c
    model/data_filter.c
    model/data_ind.c
    model/dnai_change_type.c
    model/dnn_route_selection_descriptor.c
    model/eth_flow_description.c
    model/flow_direction.c
    model/flow_info.c
    model/iptv_config_data.c
    model/iptv_config_data_patch.c
    model/limit_id_to_monitoring_key.c
    model/multicast_access_control.c
    model/network_area_info_2.c
    model/notification_item.c
    model/operator_managed.c
    model/parameter_over_pc5.c
    model/parameter_over_uu.c
    model/pc5_flow_bit_rates.c
    model/pc5_qo_s_para.c
    model/pc5_qos_flow_item.c
    model/pc5_qos_mapping.c
    model/periodicity.c
    model/pfd_change_notification.c
    model/plmn_rat_served.c
    model/plmn_route_selection_descriptor.c
    model/policy_data_change_notification.c
    model/policy_data_subscription.c
    model/pppp_to_pdb.c
    model/presence_info.c
    model/presence_state.c
    model/privacy_parameter.c
    model/radio_parameter_not_served.c
    model/resource_item.c
    model/service_application_server_address.c
    model/service_id_to_frequency.c
    model/service_id_to_layer2_id.c
    model/service_id_to_pppr.c
    model/service_parameter_data.c
    model/service_to_pdu_session.c
    model/service_to_tx.c
    model/slrb_configurations.c
    model/sm_policy_data.c
    model/sm_policy_data_patch.c
    model/sm_policy_dnn_data.c
    model/sm_policy_dnn_data_patch.c
    model/sm_policy_snssai_data.c
    model/sm_policy_snssai_data_patch.c
    model/snssai_route_selection_descriptor.c
    model/sponsor_connectivity_data.c
    model/subscribed_event.c
    model/temporal_validity.c
    model/time_period.c
    model/time_window.c
    model/traffic_influ_data.c
    model/traffic_influ_data_notif.c
    model/traffic_influ_data_patch.c
    model/traffic_influ_sub.c
    model/transfer_policy.c
    model/ue_policy_section.c
    model/ue_policy_set.c
    model/ue_policy_set_patch.c
    model/updated_item.c
    model/usage_mon_data.c
    model/usage_mon_data_limit.c
    model/usage_mon_data_scope.c
    model/usage_mon_level.c
    model/usage_threshold.c
    model/v2x_rat_type.c

    model/additional_qos_flow_info.c
    model/apn_rate_status.c
    model/cause.c
    model/cn_assisted_ran_para.c
    model/ddn_failure_subs.c
    model/dnai_information.c
    model/dnn_selection_mode.c
    model/dynamic5_qi.c
    model/ebi_arp_mapping.c
    model/eps_bearer_info.c
    model/eps_interworking_indication.c
    model/eps_pdn_cnx_info.c
    model/exemption_ind.c
    model/gbr_qos_flow_information.c
    model/ho_state.c
    model/hsmf_update_data.c
    model/hsmf_update_error.c
    model/hsmf_updated_data.c
    model/indirect_data_forwarding_tunnel_info.c
    model/inline_object.c
    model/inline_object_1.c
    model/inline_object_2.c
    model/inline_object_3.c
    model/inline_object_4.c
    model/ma_release_indication.c
    model/max_integrity_protected_data_rate.c
    model/mme_capabilities.c
    model/mo_exception_data_flag.c
    model/mo_exp_data_counter.c
    model/n2_sm_info_type.c
    model/n4_information.c
    model/n4_message_type.c
    model/ng_ap_cause.c
    model/ng_ran_target_id.c
    model/non_dynamic5_qi.c
    model/notification_cause.c
    model/notification_control.c
    model/partial_record_method.c
    model/pdu_session_create_data.c
    model/pdu_session_create_error.c
    model/pdu_session_created_data.c
    model/pdu_session_notify_item.c
    model/psa_indication.c
    model/psa_information.c
    model/qos_flow_access_type.c
    model/qos_flow_add_modify_request_item.c
    model/qos_flow_item.c
    model/qos_flow_notify_item.c
    model/qos_flow_profile.c
    model/qos_flow_release_request_item.c
    model/qos_flow_setup_item.c
    model/qos_flow_usage_report.c
    model/qos_resource_type.c
    model/ref_to_binary_data.c
    model/reflective_qo_s_attribute.c
    model/release_data.c
    model/released_data.c
    model/request_indication.c
    model/request_type.c
    model/resource_status.c
    model/roaming_charging_profile.c
    model/secondary_rat_usage_info.c
    model/secondary_rat_usage_report.c
    model/send_mo_data_req_data.c
    model/sm_context.c
    model/sm_context_create_data.c
    model/sm_context_create_error.c
    model/sm_context_created_data.c
    model/sm_context_release_data.c
    model/sm_context_released_data.c
    model/sm_context_retrieve_data.c
    model/sm_context_retrieved_data.c
    model/sm_context_status_notification.c
    model/sm_context_type.c
    model/sm_context_update_data.c
    model/sm_context_update_error.c
    model/sm_context_updated_data.c
    model/small_data_rate_status.c
    model/status_info.c
    model/status_notification.c
    model/transfer_mo_data_req_data.c
    model/transfer_mt_data_add_info.c
    model/transfer_mt_data_error.c
    model/transfer_mt_data_req_data.c
    model/trigger.c
    model/trigger_category.c
    model/trigger_type.c
    model/tunnel_info.c
    model/ulcl_bp_information.c
    model/unavailable_access_indication.c
    model/up_cnx_state.c
    model/volume_timed_report.c
    model/vplmn_qos.c
    model/vsmf_update_data.c
    model/vsmf_update_error.c
    model/vsmf_updated_data.c

    model/allowed_nssai.c
    model/allowed_snssai.c
    model/amf_event.c
    model/amf_event_area.c
    model/amf_event_mode.c
    model/amf_event_subscription.c
    model/amf_event_trigger.c
    model/amf_event_type.c
    model/amf_status_change_notification.c
    model/amf_status_change_subscription_data.c
    model/amf_status_info.c
    model/area_of_validity.c
    model/assign_ebi_data.c
    model/assign_ebi_error.c
    model/assign_ebi_failed.c
    model/assigned_ebi_data.c
    model/ciphering_algorithm.c
    model/configured_snssai.c
    model/expected_ue_behavior.c
    model/integrity_algorithm.c
    model/key_amf.c
    model/key_amf_type.c
    model/ladn_info.c
    model/location_filter.c
    model/mm_context.c
    model/n1_message_container.c
    model/n1_message_notification.c
    model/n1_n2_message_transfer_cause.c
    model/n1_n2_message_transfer_error.c
    model/n1_n2_message_transfer_req_data.c
    model/n1_n2_message_transfer_rsp_data.c
    model/n1_n2_msg_txfr_err_detail.c
    model/n1_n2_msg_txfr_failure_notification.c
    model/n2_info_container.c
    model/n2_info_content.c
    model/n2_info_notification_rsp_data.c
    model/n2_info_notify_reason.c
    model/n2_information_notification.c
    model/n2_information_transfer_error.c
    model/n2_information_transfer_req_data.c
    model/n2_information_transfer_result.c
    model/n2_information_transfer_rsp_data.c
    model/n2_ran_information.c
    model/n2_sm_information.c
    model/nas_security_mode.c
    model/ng_ksi.c
    model/ngap_ie_type.c
    model/non_ue_n2_info_subscription_create_data.c
    model/non_ue_n2_info_subscription_created_data.c
    model/nrppa_information.c
    model/nsi_information.c
    model/nssai_mapping.c
    model/pdu_session_context.c
    model/policy_req_trigger.c
    model/pws_error_data.c
    model/pws_information.c
    model/pws_response_data.c
    model/rat_selector.c
    model/registration_context_container.c
    model/sbi_binding_level.c
    model/sc_type.c
    model/seaf_data.c
    model/small_data_rate_status_info.c
    model/smf_change_indication.c
    model/smf_change_info.c
    model/status_change.c
    model/traffic_descriptor.c
    model/transfer_reason.c
    model/ue_context.c
    model/ue_context_create_data.c
    model/ue_context_create_error.c
    model/ue_context_created_data.c
    model/ue_context_release.c
    model/ue_context_transfer_req_data.c
    model/ue_context_transfer_rsp_data.c
    model/ue_context_transfer_status.c
    model/ue_n1_n2_info_subscription_create_data.c
    model/ue_n1_n2_info_subscription_created_data.c
    model/ue_reg_status_update_req_data.c
    model/ue_reg_status_update_rsp_data.c
    model/v2x_context.c

'''.split())

libsbi_openapi_inc = include_directories('.')

sbi_openapi_cc_flags = ['-DOGS_SBI_COMPILATION']

if cc.get_id() == 'gcc' or cc.get_id() == 'clang'
    sbi_openapi_cc_flags += cc.get_supported_arguments([
                    '-Wno-strict-prototypes',
                    '-Wno-missing-prototypes',
                    '-Wno-missing-declarations',
                    '-Wno-unused-variable',
                    '-Wno-unused-label',
                    '-Wno-float-equal',
    ])
endif

libsbi_openapi = library('ogssbi-openapi',
    sources : libsbi_openapi_sources,
    version : libogslib_version,
    c_args : sbi_openapi_cc_flags,
    include_directories : [libsbi_openapi_inc, libinc],
    dependencies : libcore_dep,
    install : true)

libsbi_openapi_dep = declare_dependency(
    link_with : libsbi_openapi,
    include_directories : [libsbi_openapi_inc, libinc],
    dependencies : libcore_dep)
