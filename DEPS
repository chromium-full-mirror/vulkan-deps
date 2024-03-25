# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '3225778615fd9d7e23fd11b71a05097d59ba0247',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '7d500c4d75ae3fbd37e1d5a20008ca9c8ee3c860',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'dda7731e91c130e64980d987a02f5c75356400cc',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'cfebfc96b2b0bce93da7d12f2c14cc01793ae25c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '0704d5a0e1f104f09b2dd639d0a159bcc205fd9c',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '934b5f7c13374949527b71b9732b93b5bc0fcc3e',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': '4befdac21af188a21aaf5a82702bb52a6426e47a',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '89db729bbb59be68533d25fa5faea010ba6c31d2',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
